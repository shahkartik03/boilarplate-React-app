# About

cust-hooks-use-previous gives you the previous value of state in functional component / React hook.

# Installation

npm i cust-hooks-use-previous

# Importing the hook

import { usePrevious } from 'cust-hooks-use-previous';

#Usage

const funFunction =() => {
	const prevNav = usePrevious(activeNav);
    const prevSortBy = usePrevious(sortBy);
	// prevNav will be previous value of `activeNav`.
}
