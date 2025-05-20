# Function: <code>ioc_pd_stat</code>

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
size_t ioc_pd_stat(struct blkg_policy_data *pd, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c110)
Location: block/blk-iocost.c:2984
Inline: False
```
**Symbols:**

```
ffffffff8158c110-ffffffff8158c210: ioc_pd_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t ioc_pd_stat(struct blkg_policy_data *pd, char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81592fd0)
Location: block/blk-iocost.c:2991
Inline: False
```
**Symbols:**

```
ffffffff81592fd0-ffffffff815930d0: ioc_pd_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ioc_pd_stat(struct blkg_policy_data *pd, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2998
Inline: False
```
**Symbols:**

```
ffffffff815fa800-ffffffff815fa8fa: ioc_pd_stat (STB_LOCAL)
ffffffff81cd9d49-ffffffff81cd9d72: ioc_pd_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_pd_stat(struct blkg_policy_data *pd, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3007
Inline: False
```
**Symbols:**

```
ffffffff816acc80-ffffffff816acd92: ioc_pd_stat (STB_LOCAL)
ffffffff81e8d82e-ffffffff81e8d858: ioc_pd_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_pd_stat(struct blkg_policy_data *pd, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3015
Inline: False
```
**Symbols:**

```
ffffffff8176b800-ffffffff8176b912: ioc_pd_stat (STB_LOCAL)
ffffffff82076dc7-ffffffff82076df1: ioc_pd_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_pd_stat(struct blkg_policy_data *pd, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3030
Inline: False
```
**Symbols:**

```
ffffffff817aa900-ffffffff817aaa12: ioc_pd_stat (STB_LOCAL)
ffffffff820f6c23-ffffffff820f6c4d: ioc_pd_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_pd_stat(struct blkg_policy_data *pd, struct seq_file *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3037
Inline: False
```
**Symbols:**

```
ffffffff817ee6b0-ffffffff817ee7c2: ioc_pd_stat (STB_LOCAL)
ffffffff821d4071-ffffffff821d409b: ioc_pd_stat.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file *s</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
