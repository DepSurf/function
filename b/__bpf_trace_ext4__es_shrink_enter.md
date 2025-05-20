# Function: <code>__bpf_trace_ext4__es_shrink_enter</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d450)
Location: include/trace/events/ext4.h:2381
Inline: True
```
**Symbols:**

```
ffffffff8137d450-ffffffff8137d45f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395bb0)
Location: include/trace/events/ext4.h:2421
Inline: True
```
**Symbols:**

```
ffffffff81395bb0-ffffffff81395bbf: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfb20)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813bfb20-ffffffff813bfb2f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8df0)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813d8df0-ffffffff813d8dff: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2449
Inline: False
```
**Symbols:**

```
ffffffff81426680-ffffffff8142668f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2476
Inline: False
```
**Symbols:**

```
ffffffff8143dd70-ffffffff8143dd7f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2300
Inline: False
```
**Symbols:**

```
ffffffff81443b60-ffffffff81443b6f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2300
Inline: False
```
**Symbols:**

```
ffffffff81497940-ffffffff8149794f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2306
Inline: False
```
**Symbols:**

```
ffffffff81522cc0-ffffffff81522cdb: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2343
Inline: False
```
**Symbols:**

```
ffffffff815bfd60-ffffffff815bfd7b: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2350
Inline: False
```
**Symbols:**

```
ffffffff815f74d0-ffffffff815f74eb: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: include/trace/events/ext4.h:2347
Inline: False
```
**Symbols:**

```
ffffffff81630050-ffffffff8163006b: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac3d8)
Location: include/trace/events/ext4.h:2421
Inline: True
```
**Symbols:**

```
ffff8000104ac3d8-ffff8000104ac3f4: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c06745d8)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
c06745d8-c0674610: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3fc0)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
c0000000005e3fc0-c0000000005e3ff4: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d13d0)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813d13d0-ffffffff813d13df: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1e50)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813c1e50-ffffffff813c1e5f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce860)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813ce860-ffffffff813ce86f: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4__es_shrink_enter(void *__data, struct super_block *sb, int nr_to_scan, int cache_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e3ab0)
Location: include/trace/events/ext4.h:2421
Inline: False
```
**Symbols:**

```
ffffffff813e3ab0-ffffffff813e3abf: __bpf_trace_ext4__es_shrink_enter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
