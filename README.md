# email-permutator

## This is very simple email permutator

## Example usage.

###Initialize object:

var emailPermulator = new EmailPermutator('foo', 'master', 'gmail.com');

emailPermulator.addSpecialCharBetweenNames();

emailPermulator.addEmailByFirstCharCombination();

emailPermulator.addSpecialCharBetweenNames();

###Get emails:

emailPermulator.availableEmail();

### Sample results:

foo-master@gmail.com
master-foo@gmail.com
f-master@gmail.com
foo-m@gmail.com
f-m@gmail.com
foo.master@gmail.com
master.foo@gmail.com
f.master@gmail.com
foo.m@gmail.com
f.m@gmail.com
foo_master@gmail.com
master_foo@gmail.com
f_master@gmail.com
foo_m@gmail.com
f_m@gmail.com
foomaster@gmail.com
masterfoo@gmail.com
masterf@gmail.com
m.f@gmail.com
m.foo@gmail.com
mf@gmail.com
fmaster@gmail.com
foom@gmail.com
fm@gmail.com
foo-master@gmail.com
master-foo@gmail.com
f-master@gmail.com
foo-m@gmail.com
f-m@gmail.com
foo.master@gmail.com
master.foo@gmail.com
f.master@gmail.com
foo.m@gmail.com
f.m@gmail.com
foo_master@gmail.com
master_foo@gmail.com
f_master@gmail.com
foo_m@gmail.com
f_m@gmail.com
foomaster@gmail.com
masterfoo@gmail.com
masterf@gmail.com
m.f@gmail.com
m.foo@gmail.com
mf@gmail.com
