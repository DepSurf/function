# Function: <code>target_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int target_message(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a8a80)
Location: drivers/md/dm-ioctl.c:1511
Inline: False
```
**Symbols:**

```
ffffffff816a8a80-ffffffff816a8d87: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int target_message(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81708f10)
Location: drivers/md/dm-ioctl.c:1521
Inline: False
```
**Symbols:**

```
ffffffff81708f10-ffffffff81709204: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int target_message(struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173ade0)
Location: drivers/md/dm-ioctl.c:1521
Inline: False
```
**Symbols:**

```
ffffffff8173ade0-ffffffff8173b0d4: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81754750)
Location: drivers/md/dm-ioctl.c:1539
Inline: False
```
**Symbols:**

```
ffffffff81754750-ffffffff81754a7b: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c6900)
Location: drivers/md/dm-ioctl.c:1546
Inline: False
```
**Symbols:**

```
ffffffff817c6900-ffffffff817c6c2e: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1547
Inline: False
```
**Symbols:**

```
ffffffff81810030-ffffffff818102d7: target_message (STB_LOCAL)
ffffffff81811892-ffffffff8181195d: target_message.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1547
Inline: False
```
**Symbols:**

```
ffffffff8183c030-ffffffff8183c2d7: target_message (STB_LOCAL)
ffffffff8183d85b-ffffffff8183d905: target_message.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1547
Inline: False
```
**Symbols:**

```
ffffffff8187e230-ffffffff8187e4c2: target_message (STB_LOCAL)
ffffffff81880393-ffffffff81880479: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff818b03c0-ffffffff818b0651: target_message (STB_LOCAL)
ffffffff818b2253-ffffffff818b2339: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff81980570-ffffffff81980828: target_message (STB_LOCAL)
ffffffff81982917-ffffffff819829f8: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff81984b90-ffffffff81984e48: target_message (STB_LOCAL)
ffffffff81c2825b-ffffffff81c28336: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1649
Inline: False
```
**Symbols:**

```
ffffffff8196a2d0-ffffffff8196a588: target_message (STB_LOCAL)
ffffffff81c1a645-ffffffff81c1a720: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81a12770-ffffffff81a12a28: target_message (STB_LOCAL)
ffffffff81d2a4ac-ffffffff81d2a587: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1671
Inline: False
```
**Symbols:**

```
ffffffff81b7af60-ffffffff81b7b25f: target_message (STB_LOCAL)
ffffffff81ef672d-ffffffff81ef67cb: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d175f0)
Location: drivers/md/dm-ioctl.c:1678
Inline: False
```
**Symbols:**

```
ffffffff81d175f0-ffffffff81d1798b: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81d80880)
Location: drivers/md/dm-ioctl.c:1742
Inline: False
```
**Symbols:**

```
ffffffff81d80880-ffffffff81d80c1b: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81e37ee0)
Location: drivers/md/dm-ioctl.c:1747
Inline: False
```
**Symbols:**

```
ffffffff81e37ee0-ffffffff81e3827b: target_message (STB_LOCAL)
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
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b074a0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffff800010b074a0-ffff800010b077d0: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be5f94)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
c0be5f94-c0be62ac: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf8420)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
c000000000bf8420-c000000000bf8864: target_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f5d96)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffe0006f5d96-ffffffe0006f6064: target_message (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff81856240-ffffffff818564d1: target_message (STB_LOCAL)
ffffffff818580d3-ffffffff818581b9: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff8181d850-ffffffff8181dae1: target_message (STB_LOCAL)
ffffffff8181f6e3-ffffffff8181f7c9: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff818a5870-ffffffff818a5b01: target_message (STB_LOCAL)
ffffffff818a7703-ffffffff818a77e9: target_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int target_message(struct file *filp, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:1572
Inline: False
```
**Symbols:**

```
ffffffff818c1ab0-ffffffff818c1d41: target_message (STB_LOCAL)
ffffffff818c3943-ffffffff818c3a29: target_message.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param reordered. </b>
<code>param, param_size</code> ➡️ <code>filp, param, param_size</code>
</li>
</ul>
</details>
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
