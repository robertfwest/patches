Patches to open source projects written by yours truly.

net-snmp-5.4.2.1-oidcore.patch
------------------------------
- Fixed snmpd segfault due to a corrupted stack frame caused when parsing an
  oversized OID from an AgentX subagent
- Report: 
  http://sourceforge.net/tracker/?func=detail&atid=312694&aid=2956657&group_id=12694
- Accepted by upstream with minor modifications and integrated into several versions:
  * 5.2: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=b4a219cf17530721c7624747e162a0e78aa11057
  * 5.3: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=a999259c966855ede40df23bdc49a52e5b8564cd
  * 5.4: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=36782f4e09c5f3b6be64c2e0bd490ce56a0d689f
  * 5.6: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=df3161738a15af84813c9a7777be1f55d747b01d

vpnc
----
- Ubuntu bug originally reported by Reece: 
  https://bugs.launchpad.net/debian/+source/vpnc/+bug/214399
- Ubuntu patch for Debian: 
  http://bugs.debian.org/cgi-bin/bugreport.cgi?msg=5;filename=07_fix_double_password_prompt.dpatch;att=1;bug=492981
- Discussion with maintainer:
  * http://lists.unix-ag.uni-kl.de/pipermail/vpnc-devel/2008-June/002376.html
  * http://lists.unix-ag.uni-kl.de/pipermail/vpnc-devel/2008-June/002422.html
  * http://lists.unix-ag.uni-kl.de/pipermail/vpnc-devel/2008-June/002443.html
- Commit message: http://lists.unix-ag.uni-kl.de/pipermail/vpnc-devel/2008-June/002423.html
- Mention in changelog:
  http://lists.unix-ag.uni-kl.de/pipermail/vpnc-devel/2008-November/002728.html

Ruby On Rails
-------------
- Report: http://markmail.org/thread/xri63bdrrhqtmzk3

Parrot
------
- Report: http://www.nntp.perl.org/group/perl.perl6.internals/2007/10/msg40729.html
- Accepted by Jerry Gay (particle): 
  * Email: http://www.nntp.perl.org/group/perl.perl6.internals/2007/10/msg40800.html 
  * Commit: https://github.com/parrot/parrot/commit/3ccc147d76b9d616a5724c0d2d9822bc25c4a588

VIM
---
- Report: http://comments.gmane.org/gmane.editors.vim.devel/602
- CVS: http://vim.cvs.sourceforge.net/viewvc/vim/vim/src/syntax.c?revision=1.67&view=markup
- In documentation (do :help fixed-6.2 and search for "Patch 6.1.200"):
  http://code.google.com/p/vim/source/browse/runtime/doc/version6.txt#7747

IPVSAdm
-------
- Commit: https://github.com/horms/ipvsadm-test/commit/59b79515af7010d6e8461918ab7e2e1dc08bc603

