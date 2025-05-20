# Function: <code>proc_put_long</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81087aa0)
Location: kernel/sysctl.c:2009
Inline: False
Direct callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
```
**Symbols:**

```
ffffffff81087aa0-ffffffff81087b4d: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108b080)
Location: kernel/sysctl.c:2129
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108b080-ffffffff8108b174: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108ffd0)
Location: kernel/sysctl.c:2114
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108ffd0-ffffffff810900c4: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108c8c0)
Location: kernel/sysctl.c:2138
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8108c8c0-ffffffff8108c9a6: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093dc0)
Location: kernel/sysctl.c:2130
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff81093dc0-ffffffff81093ed8: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2135
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810977e0-ffffffff810978b6: proc_put_long (STB_LOCAL)
ffffffff81098d22-ffffffff81098d3a: proc_put_long.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2183
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8109fb30-ffffffff8109fc06: proc_put_long (STB_LOCAL)
ffffffff810a10a4-ffffffff810a10bc: proc_put_long.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2269
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a41f0-ffffffff810a42c6: proc_put_long (STB_LOCAL)
ffffffff810a5afa-ffffffff810a5b12: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810aa7d0-ffffffff810aa8a6: proc_put_long (STB_LOCAL)
ffffffff810ac0da-ffffffff810ac0f2: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:500
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810b1d80-ffffffff810b1ea6: proc_put_long (STB_LOCAL)
ffffffff810b3c5a-ffffffff810b3c72: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:499
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810ad5b0-ffffffff810ad6d6: proc_put_long (STB_LOCAL)
ffffffff81bdb896-ffffffff81bdb8ae: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:511
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810ae7c0-ffffffff810ae8e8: proc_put_long (STB_LOCAL)
ffffffff81bcd988-ffffffff81bcd9a0: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:520
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810c0340-ffffffff810c0468: proc_put_long (STB_LOCAL)
ffffffff81ca4370-ffffffff81ca4388: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:400
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810d7950-ffffffff810d7aab: proc_put_long (STB_LOCAL)
ffffffff81e53c04-ffffffff81e53c1c: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f75c0)
Location: kernel/sysctl.c:402
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810f75c0-ffffffff810f7733: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff811039c0)
Location: kernel/sysctl.c:401
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff811039c0-ffffffff81103b33: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110d310)
Location: kernel/sysctl.c:401
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff8110d310-ffffffff8110d483: proc_put_long (STB_LOCAL)
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
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010102bb8)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffff800010102bb8-ffff800010102dfc: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c035ed18)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
c035ed18-c035ee70: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014a910)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
c00000000014a910-c00000000014aa60: proc_put_long (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000c8f6a)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffe0000c8f6a-ffffffe0000c901a: proc_put_long (STB_LOCAL)
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
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a40f0-ffffffff810a41c6: proc_put_long (STB_LOCAL)
ffffffff810a59fa-ffffffff810a5a12: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff81092ad0-ffffffff81092ba6: proc_put_long (STB_LOCAL)
ffffffff810943da-ffffffff810943f2: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810a40a0-ffffffff810a4176: proc_put_long (STB_LOCAL)
ffffffff810a59aa-ffffffff810a59c2: proc_put_long.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proc_put_long(void **buf, size_t *size, long unsigned int val, bool neg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (0)
Location: kernel/sysctl.c:2271
Inline: False
Direct callers:
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff810ac160-ffffffff810ac236: proc_put_long (STB_LOCAL)
ffffffff810ada6a-ffffffff810ada82: proc_put_long.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
