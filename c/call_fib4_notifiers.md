# Function: <code>call_fib4_notifiers</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff818e22d0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff818e22d0-ffffffff818e2334: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81938de0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff81938de0-ffffffff81938e51: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81968810)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff81968810-ffffffff81968881: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff819cebd0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff819cebd0-ffffffff819cec44: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81a05760)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff81a05760-ffffffff81a057d4: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81af4d80)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:__fib_info_notify_update
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81af4d80-ffffffff81af4df4: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81b01b80)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81b01b80-ffffffff81b01bf4: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81aed490)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81aed490-ffffffff81aed504: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_notifier.c (0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81d3dad0-ffffffff81d3dae4: call_fib4_notifiers.cold (STB_LOCAL)
ffffffff81bad840-ffffffff81bad8c2: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_notifier.c (0)
Location: net/ipv4/fib_notifier.c:19
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81f0a3b8-ffffffff81f0a3cd: call_fib4_notifiers.cold (STB_LOCAL)
ffffffff81d40890-ffffffff81d4091d: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_notifier.c (0)
Location: net/ipv4/fib_notifier.c:19
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff820b1c81-ffffffff820b1c96: call_fib4_notifiers.cold (STB_LOCAL)
ffffffff81f09580-ffffffff81f0960d: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_notifier.c (0)
Location: net/ipv4/fib_notifier.c:19
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff82132eb9-ffffffff82132ece: call_fib4_notifiers.cold (STB_LOCAL)
ffffffff81f69090-ffffffff81f6911d: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_notifier.c (0)
Location: net/ipv4/fib_notifier.c:19
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:fib_notify_alias_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8221489a-ffffffff822148af: call_fib4_notifiers.cold (STB_LOCAL)
ffffffff8202f710-ffffffff8202f79d: call_fib4_notifiers (STB_GLOBAL)
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
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffff800010cbe3a8)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffff800010cbe3a8-ffff800010cbe440: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (c0dc9d98)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
c0dc9d98-c0dc9e34: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (c000000000dd8a00)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
c000000000dd8a00-c000000000dd8ad0: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffe0008144dc)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffe0008144dc-ffffffe000814562: call_fib4_notifiers (STB_GLOBAL)
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
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff819a5500)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff819a5500-ffffffff819a5574: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff8195efc0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff8195efc0-ffffffff8195f034: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81a0fda0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff81a0fda0-ffffffff81a0fe14: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net *net, enum fib_event_type event_type, struct fib_notifier_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_notifier.c (ffffffff81a1a5f0)
Location: net/ipv4/fib_notifier.c:20
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_trie.c:call_fib_entry_notifiers
```
**Symbols:**

```
ffffffff81a1a5f0-ffffffff81a1a664: call_fib4_notifiers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
