# Function: <code>sock_hash_seq_show</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53a80)
Location: net/core/sock_map.c:1363
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81a53a80-ffffffff81a53b35: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f580)
Location: net/core/sock_map.c:1346
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81a4f580-ffffffff81a4f635: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b081c0)
Location: net/core/sock_map.c:1337
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81b081c0-ffffffff81b08275: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8e0f0)
Location: net/core/sock_map.c:1339
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81c8e0f0-ffffffff81c8e1bf: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e490c0)
Location: net/core/sock_map.c:1341
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81e490c0-ffffffff81e4918f: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea47e0)
Location: net/core/sock_map.c:1344
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81ea47e0-ffffffff81ea48af: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_hash_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67200)
Location: net/core/sock_map.c:1350
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_seq_stop
```
**Symbols:**

```
ffffffff81f67200-ffffffff81f672cf: sock_hash_seq_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
