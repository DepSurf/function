# Function: <code>do_proc_douintvec_conv</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_proc_douintvec_conv(bool *negp, long unsigned int *lvalp, int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108a9a0)
Location: kernel/sysctl.c:2186
Inline: False
```
**Symbols:**

```
ffffffff8108a9a0-ffffffff8108a9cb: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_proc_douintvec_conv(bool *negp, long unsigned int *lvalp, int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108f8f0)
Location: kernel/sysctl.c:2171
Inline: False
```
**Symbols:**

```
ffffffff8108f8f0-ffffffff8108f91b: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108c890)
Location: kernel/sysctl.c:2195
Inline: False
```
**Symbols:**

```
ffffffff8108c890-ffffffff8108c8c0: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810935d0)
Location: kernel/sysctl.c:2187
Inline: False
```
**Symbols:**

```
ffffffff810935d0-ffffffff81093600: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81097030)
Location: kernel/sysctl.c:2192
Inline: False
```
**Symbols:**

```
ffffffff81097030-ffffffff81097060: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109f360)
Location: kernel/sysctl.c:2240
Inline: False
```
**Symbols:**

```
ffffffff8109f360-ffffffff8109f390: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a3a5d)
Location: kernel/sysctl.c:2326
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810a3a20-ffffffff810a3a50: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aa04d)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810aa010-ffffffff810aa040: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b1bed)
Location: kernel/sysctl.c:554
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810b1bb0-ffffffff810b1be0: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ad41d)
Location: kernel/sysctl.c:553
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810ad3e0-ffffffff810ad410: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae61d)
Location: kernel/sysctl.c:565
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810ae5e0-ffffffff810ae60f: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c019d)
Location: kernel/sysctl.c:589
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810c0160-ffffffff810c018f: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d775d)
Location: kernel/sysctl.c:469
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810d7700-ffffffff810d7747: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f726d)
Location: kernel/sysctl.c:456
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810f7200-ffffffff810f7247: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81103659)
Location: kernel/sysctl.c:455
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff811035f0-ffffffff81103637: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110cfa9)
Location: kernel/sysctl.c:455
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff8110cf40-ffffffff8110cf87: do_proc_douintvec_conv (STB_LOCAL)
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
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff8000101022d4)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffff800010102230-ffff8000101022a4: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035e300)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
c035e2b0-c035e2e0: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c0000000001499c4)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
c000000000149950-c0000000001499a8: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000c8f0e)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffe0000c8e8e-ffffffe0000c8ee8: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a396d)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810a3930-ffffffff810a3960: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109234d)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff81092310-ffffffff81092340: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a391d)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810a38e0-ffffffff810a3910: do_proc_douintvec_conv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_proc_douintvec_conv(long unsigned int *lvalp, unsigned int *valp, int write, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ab9dd)
Location: kernel/sysctl.c:2328
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_douintvec_minmax_conv
```
**Symbols:**

```
ffffffff810ab9a0-ffffffff810ab9d0: do_proc_douintvec_conv (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *negp</code>
</li>
<li>
<b>Param reordered. </b>
<code>negp, lvalp, valp, write, data</code> ➡️ <code>lvalp, valp, write, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int *valp</code> ➡️ <code>unsigned int *valp</code>
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
