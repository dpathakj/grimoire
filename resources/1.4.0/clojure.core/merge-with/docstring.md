Returns a map that consists of the rest of the maps conj-ed ontothe first.  If a key occurs in more than one map, the mapping(s)from the latter (left-to-right) will be combined with the mapping inthe result by calling (f val-in-result val-in-latter).