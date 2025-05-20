# Function: <code>call_fib_notifiers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183d656)
Location: net/ipv4/fib_trie.c:189
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
Direct callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff8183f690-ffffffff8183f6b3: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81862280)
Location: net/ipv4/fib_notifier.c:19
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
**Symbols:**

```
ffffffff81862280-ffffffff818622a3: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8186a4a0)
Location: net/core/fib_notifier.c:21
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:call_ipmr_mfc_entry_notifiers
  - net/ipv4/ipmr.c:call_ipmr_vif_entry_notifiers
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
```
**Symbols:**

```
ffffffff8186a4a0-ffffffff8186a4bc: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818ba1f0)
Location: net/core/fib_notifier.c:24
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818ba1f0-ffffffff818ba225: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818e1070)
Location: net/core/fib_notifier.c:24
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818e1070-ffffffff818e10a5: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff8192f860)
Location: net/core/fib_notifier.c:24
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff8192f860-ffffffff8192f893: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81961ad0)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81961ad0-ffffffff81961b03: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a350d0)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a350d0-ffffffff81a3510e: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a373d0)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a373d0-ffffffff81a37426: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81a1e530)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81a1e530-ffffffff81a1e585: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81ad25d0)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81ad25d0-ffffffff81ad2625: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81c4ffe0)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81c4ffe0-ffffffff81c5004e: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e05340)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81e05340-ffffffff81e053ae: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81e77b90)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81e77b90-ffffffff81e77bfe: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81f37b50)
Location: net/core/fib_notifier.c:29
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81f37b50-ffffffff81f37bbe: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffff800010c05788)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffff800010c05788-ffff800010c057ec: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c0d1e880)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c0d1e880-c0d1e8bc: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (c000000000cef910)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
c000000000cef910-c000000000cef984: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffe000783f84)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffe000783f84-ffffffe000783fee: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81901aa0)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81901aa0-ffffffff81901ad3: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff818bb8d0)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff818bb8d0-ffffffff818bb903: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81952ad0)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81952ad0-ffffffff81952b03: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/fib_notifier.c (ffffffff81974510)
Location: net/core/fib_notifier.c:31
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/fib_notifier.c:call_fib4_notifiers
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv6/fib6_notifier.c:call_fib6_notifiers
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:mif6_delete
```
**Symbols:**

```
ffffffff81974510-ffffffff81974543: call_fib_notifiers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
