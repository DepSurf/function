# Function: <code>__add_hash_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114039c)
Location: kernel/trace/ftrace.c:1249
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:add_hash_entry
  - kernel/trace/ftrace.c:ftrace_hash_move
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81148680)
Location: kernel/trace/ftrace.c:1218
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81148680-ffffffff811486cc: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81152530)
Location: kernel/trace/ftrace.c:1224
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81152530-ffffffff8115257c: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154ad0)
Location: kernel/trace/ftrace.c:1249
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81154ad0-ffffffff81154b1f: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161300)
Location: kernel/trace/ftrace.c:1225
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81161300-ffffffff8116134f: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170240)
Location: kernel/trace/ftrace.c:1214
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81170240-ffffffff8117028a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117ddf0)
Location: kernel/trace/ftrace.c:1163
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff8117ddf0-ffffffff8117de3a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118ace0)
Location: kernel/trace/ftrace.c:1160
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff8118ace0-ffffffff8118ad2a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196bd0)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81196bd0-ffffffff81196c1a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811add7a)
Location: kernel/trace/ftrace.c:1149
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811abed0-ffffffff811abf1a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ab689)
Location: kernel/trace/ftrace.c:1148
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811a9790-ffffffff811a97da: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac118)
Location: kernel/trace/ftrace.c:1148
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811aa340-ffffffff811aa391: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d5e02)
Location: kernel/trace/ftrace.c:1149
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811d41a0-ffffffff811d420d: __add_hash_entry (STB_LOCAL)
ffffffff81cb4049-ffffffff81cb406d: __add_hash_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120b002)
Location: kernel/trace/ftrace.c:1143
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
```
**Symbols:**

```
ffffffff81208df0-ffffffff81208e6b: __add_hash_entry (STB_LOCAL)
ffffffff81e64f92-ffffffff81e64fb6: __add_hash_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81253942)
Location: kernel/trace/ftrace.c:1143
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
```
**Symbols:**

```
ffffffff812513f0-ffffffff8125146b: __add_hash_entry (STB_LOCAL)
ffffffff8205ca85-ffffffff8205caa9: __add_hash_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126ad62)
Location: kernel/trace/ftrace.c:1174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:dup_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff81268870-ffffffff812688eb: __add_hash_entry (STB_LOCAL)
ffffffff820db426-ffffffff820db44a: __add_hash_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812850cf)
Location: kernel/trace/ftrace.c:1174
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_move
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
```
**Symbols:**

```
ffffffff81282ae0-ffffffff81282b5b: __add_hash_entry (STB_LOCAL)
ffffffff821b7147-ffffffff821b716b: __add_hash_entry.cold (STB_LOCAL)
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
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f1c0)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffff80001020f1c0-ffff80001020f220: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0453c00)
Location: kernel/trace/ftrace.c:1161
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028d890)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
c00000000028d890-c00000000028d8f8: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00016fcbe)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffe00016fcbe-ffffffe00016fd04: __add_hash_entry (STB_LOCAL)
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
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f1f0)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff8118f1f0-ffffffff8118f23a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182330)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff81182330-ffffffff8118237a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118cfc0)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff8118cfc0-ffffffff8118d00a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __add_hash_entry(struct ftrace_hash *hash, struct ftrace_func_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ab20)
Location: kernel/trace/ftrace.c:1161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:add_hash_entry
```
**Symbols:**

```
ffffffff8119ab20-ffffffff8119ab6a: __add_hash_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
