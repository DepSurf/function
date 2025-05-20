# Function: <code>sync_print_sync_file</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8162cb57)
Location: drivers/dma-buf/sync_debug.c:133
Inline: True
Inline callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81642060)
Location: drivers/dma-buf/sync_debug.c:132
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff81642060-ffffffff8164214d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff816ab070)
Location: drivers/dma-buf/sync_debug.c:130
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff816ab070-ffffffff816ab15d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff816e7570)
Location: drivers/dma-buf/sync_debug.c:130
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff816e7570-ffffffff816e765d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8170a900)
Location: drivers/dma-buf/sync_debug.c:130
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
```
**Symbols:**

```
ffffffff8170a900-ffffffff8170a9ed: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81746180)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff81746180-ffffffff8174626d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8176a2d0)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff8176a2d0-ffffffff8176a3bd: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8182c3f0)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff8182c3f0-ffffffff8182c4dd: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8183d450)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff8183d450-ffffffff8183d53d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff818205e0)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff818205e0-ffffffff818206cd: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff818aacb0)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff818aacb0-ffffffff818aad9d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff819f5300)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff819f5300-ffffffff819f5410: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81b72800)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff81b72800-ffffffff81b72910: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81bc6200)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff81bc6200-ffffffff81bc6310: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81c1ad20)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff81c1ad20-ffffffff81c1ae30: sync_print_sync_file (STB_LOCAL)
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
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffff80001096beb8)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffff80001096beb8-ffff80001096bfc4: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (c0a41a2c)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
c0a41a2c-c0a41b40: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (c000000000a24960)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
c000000000a24960-c000000000a24ae8: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffe0005d6cda)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffe0005d6cda-ffffffe0005d6db2: sync_print_sync_file (STB_LOCAL)
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
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8171e9c0)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff8171e9c0-ffffffff8171eaad: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff816f7e00)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff816f7e00-ffffffff816f7eed: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff8175d790)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff8175d790-ffffffff8175d87d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_print_sync_file(struct seq_file *s, struct sync_file *sync_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sync_debug.c (ffffffff81778e20)
Location: drivers/dma-buf/sync_debug.c:121
Inline: False
Direct callers:
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
```
**Symbols:**

```
ffffffff81778e20-ffffffff81778f0d: sync_print_sync_file (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
