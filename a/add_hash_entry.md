# Function: <code>add_hash_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140370)
Location: kernel/trace/ftrace.c:1265
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81140370-ffffffff811403f6: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811489a0)
Location: kernel/trace/ftrace.c:1234
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811489a0-ffffffff811489e5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81152850)
Location: kernel/trace/ftrace.c:1240
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff81152850-ffffffff81152895: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81154eb0)
Location: kernel/trace/ftrace.c:1261
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff81154eb0-ffffffff81154ef5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161770)
Location: kernel/trace/ftrace.c:1237
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff81161770-ffffffff811617b5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811706a0)
Location: kernel/trace/ftrace.c:1226
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811706a0-ffffffff811706e5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117e090)
Location: kernel/trace/ftrace.c:1175
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff8117e090-ffffffff8117e0d5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118b080)
Location: kernel/trace/ftrace.c:1172
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff8118b080-ffffffff8118b0c5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81197030)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff81197030-ffffffff81197075: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0de8)
Location: kernel/trace/ftrace.c:1161
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811ae0a0-ffffffff811ae120: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae858)
Location: kernel/trace/ftrace.c:1160
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811ab9b0-ffffffff811aba30: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af1f6)
Location: kernel/trace/ftrace.c:1160
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:match_records
Direct callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
```
**Symbols:**

```
ffffffff811ac440-ffffffff811ac4c4: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d9037)
Location: kernel/trace/ftrace.c:1161
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120fdd6)
Location: kernel/trace/ftrace.c:1155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81259196)
Location: kernel/trace/ftrace.c:1155
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81270566)
Location: kernel/trace/ftrace.c:1186
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct ftrace_func_entry *add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81285c72)
Location: kernel/trace/ftrace.c:1187
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:enter_record
```
**Symbols:**

```
ffffffff81285500-ffffffff812855c9: add_hash_entry (STB_LOCAL)
ffffffff821b7383-ffffffff821b73a7: add_hash_entry.cold (STB_LOCAL)
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
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f480)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffff80001020f480-ffff80001020f4d4: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e3b8)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
c044e3b8-c044e450: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028e220)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
c00000000028e220-c00000000028e298: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017019e)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffe00017019e-ffffffe0001701e8: add_hash_entry (STB_LOCAL)
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
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f650)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff8118f650-ffffffff8118f695: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182790)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff81182790-ffffffff811827d5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d420)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff8118d420-ffffffff8118d465: add_hash_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_hash_entry(struct ftrace_hash *hash, long unsigned int ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119afa0)
Location: kernel/trace/ftrace.c:1173
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
```
**Symbols:**

```
ffffffff8119afa0-ffffffff8119afe5: add_hash_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
