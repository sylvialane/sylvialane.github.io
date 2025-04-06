.PHONY: local test live all

local:
	jekyll build --safe -d ./lanes
	(sleep 1 && open "http://127.0.0.1:4000") &
	jekyll serve

test:
	jekyll build --safe -d /Volumes/test.computational.linguistics.illinois.edu/lanes

live:
	jekyll build --safe -d /Volumes/computational.linguistics.illinois.edu/lanes

all: local live
