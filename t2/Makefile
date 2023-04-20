run:
	testscript issue2356.txtar

expand:
	txtar-x issue2356.txtar

export:
	rm -f mytest.cue
	txtar-x issue2356.txtar
	cue export mytest.cue

exportyaml:
	rm -f mytest.cue
	txtar-x issue2356.txtar
	cue export mytest.cue --out yaml

clean:
	rm -f *.cue
