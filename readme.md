this repo is for my wip font family "fail". it will start with just basic latin character set in a single weight grotesque.

ROADMAP:
- complete first
family: fail: {
	style: grotesque
	kind: roman
	use: text
	weight: regular
	proportion: normal
	character-set: basic latin
}

family: fail: {
	style: {
		serif,
		grotesque
	}
	kind: {
		roman
		slanted: {
			italic,
			oblique
		}
	}
	use: {
		text,
		display
	}
	weight: {
		light,
		thin,
		regular,
		bold,
		heavy
	}
	proportion: {
		condensed,
		normal,
		expanded,
	}
	character-sets: {
		basic latin
		latin-1 supplement
		latin extended-a
		latin extended-b
		general punctuation
		mathematical operators
		misc symbols
	}
}
