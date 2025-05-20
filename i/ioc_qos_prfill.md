# Function: <code>ioc_qos_prfill</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815102a0)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffff815102a0-ffffffff815103be: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815715c0)
Location: block/blk-iocost.c:2199
Inline: False
```
**Symbols:**

```
ffffffff815715c0-ffffffff815716df: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c680)
Location: block/blk-iocost.c:3103
Inline: False
```
**Symbols:**

```
ffffffff8158c680-ffffffff8158c79f: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815933c0)
Location: block/blk-iocost.c:3110
Inline: False
```
**Symbols:**

```
ffffffff815933c0-ffffffff815934df: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3112
Inline: False
```
**Symbols:**

```
ffffffff815fa900-ffffffff815faa34: ioc_qos_prfill (STB_LOCAL)
ffffffff81cd9d72-ffffffff81cd9dbb: ioc_qos_prfill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3120
Inline: False
```
**Symbols:**

```
ffffffff816acda0-ffffffff816aceee: ioc_qos_prfill (STB_LOCAL)
ffffffff81e8d858-ffffffff81e8d8a1: ioc_qos_prfill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3128
Inline: False
```
**Symbols:**

```
ffffffff8176b930-ffffffff8176ba7e: ioc_qos_prfill (STB_LOCAL)
ffffffff82076df1-ffffffff82076e3a: ioc_qos_prfill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3147
Inline: False
```
**Symbols:**

```
ffffffff817aaa30-ffffffff817aabaa: ioc_qos_prfill (STB_LOCAL)
ffffffff820f6c4d-ffffffff820f6c96: ioc_qos_prfill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3154
Inline: False
```
**Symbols:**

```
ffffffff817ee7e0-ffffffff817ee95a: ioc_qos_prfill (STB_LOCAL)
ffffffff821d409b-ffffffff821d40e4: ioc_qos_prfill.cold (STB_LOCAL)
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
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613a60)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffff800010613a60-ffff800010613b68: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bf26c)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
c07bf26c-c07bf3ac: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b2cd0)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
c0000000007b2cd0-c0000000007b2e5c: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b46e)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffe00044b46e-ffffffe00044b538: ioc_qos_prfill (STB_LOCAL)
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
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508880)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffff81508880-ffffffff8150899e: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8d30)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffff814f8d30-ffffffff814f8e4e: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504910)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffff81504910-ffffffff81504a2e: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 ioc_qos_prfill(struct seq_file *sf, struct blkg_policy_data *pd, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151df30)
Location: block/blk-iocost.c:2133
Inline: False
```
**Symbols:**

```
ffffffff8151df30-ffffffff8151e04e: ioc_qos_prfill (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
