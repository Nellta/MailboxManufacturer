# MailboxManufacturer
Kattis Problem id  : mailbox

In the good old days when Swedish children were still allowed to blow up their fingers with fire-crackers, gangs of excited kids would plague certain smaller cities during Easter time, with only one thing in mind: To blow things up. Small boxes were easy to blow up, and thus mailboxes became a popular target. Now, a small mailbox manufacturer is interested in how many fire-crackers his new mailbox prototype can withstand without exploding and has hired you to help him. He will provide you with
k
k
(
1≤k≤10
1≤k≤10
) identical mailbox prototypes each fitting up to
m
m
(
1≤m≤100
1≤m≤100
) crackers.
However, he is not sure of how many fire-crackers he needs to provide you with in order for you to be able to solve his problem, so he asks you. You think for a while and then say:
“Well, if I blow up a mailbox I can’t use it again, so if you would provide me with only
k=1
k=1
mailboxes, I would have to start testing with
1
1
cracker, then
2
2
crackers, and so on until it finally exploded. In the worst case, that is if it does not blow up even when filled with
m
m
crackers, I would need
1+2+3+…+m=
m(m+1)
2

1+2+3+…+m=m(m+1)2
crackers. If
m=100
m=100
that would mean more than
5000
5000
fire-crackers!”
“That’s too many”, he replies. “What if I give you more than
k=1
k=1
mailboxes? Can you find a strategy that requires fewer fire crackers?”
Can you? And what is the minimum number of crackers that you should ask him to provide you with?
You may assume the following:
If a mailbox can withstand
x
x
fire-crackers, it can also withstand
x−1
x−1
fire-crackers.
Upon an explosion, a mailbox is either totally destroyed (blown up) or unharmed, which means that it can be reused in another test explosion.
Note: If the mailbox can withstand a full load of
m
m
fire-crackers, then the manufacturer will of course be satisfied with that answer. But otherwise he is looking for the maximum number of crackers that his mailboxes can withstand.
