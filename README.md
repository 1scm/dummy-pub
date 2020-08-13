# dummy-pub
public dummy \
TC3: 'write" role to create a new branch - succeed\
TC4: 'write' role to push to protected master - fail\
TC5: 'maintainer' role to push to protected master - fail \
TC6: 'admin' role to push to protected master - succeed \
TC7: 'write' role to merge PR - succeed \
TC8: 'write' role to merge PR (enable "branch restriction" in protection rule) - fail \
TC9: 'maintainer' role to merge PR (enable "branch restriction" in protection rule) - succeed \
TC10: 'write" role to create a new branch (enable "branch restriction")- succeed\
TC11: 'read' to approve PR\
