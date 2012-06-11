Patches to open source projects written by yours truly.

net-snmp-5.4.2.1-oidcore.patch
------------------------------
- Fixed snmpd segfault due to a corrupted stack frame caused when parsing an oversized OID from an AgentX subagent
- Report: http://sourceforge.net/tracker/?func=detail&atid=312694&aid=2956657&group_id=12694
- Accepted by upstream with minor modifications and integrated into several versions:
  * 5.2: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=b4a219cf17530721c7624747e162a0e78aa11057
  * 5.3: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=a999259c966855ede40df23bdc49a52e5b8564cd
  * 5.4: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=36782f4e09c5f3b6be64c2e0bd490ce56a0d689f
  * 5.6: http://net-snmp.git.sourceforge.net/git/gitweb.cgi?p=net-snmp/net-snmp;a=commit;h=df3161738a15af84813c9a7777be1f55d747b01d


