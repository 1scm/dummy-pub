# dummy-pub
public dummy \
TC4: 'write' role to push to protected master - fail\
TC5: 'maintainer' role to push to protected master - fail \
TC6: 'admin' role to push to protected master - succeed \
TC7: 'write' role to merge PR - succeed \
TC8: 'write' role to merge PR (enable "restrict who can push" rule) - fail \
TC9: 'maintainer' role to merge PR (enable "restrict who can push" rule) - succeed\
