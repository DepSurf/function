# Function: <code>aio_nr_sub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125b400)
Location: fs/aio.c:677
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:SyS_io_setup
```
**Symbols:**

```
ffffffff8125b400-ffffffff8125b460: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81283ff0)
Location: fs/aio.c:687
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:kill_ioctx
```
**Symbols:**

```
ffffffff81283ff0-ffffffff8128404c: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297c60)
Location: fs/aio.c:690
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81297c60-ffffffff81297cbc: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a5a50)
Location: fs/aio.c:689
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812a5a50-ffffffff812a5aa0: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c8f70)
Location: fs/aio.c:712
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812c8f70-ffffffff812c8fc0: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f2aa0)
Location: fs/aio.c:675
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812f2aa0-ffffffff812f2aea: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307810)
Location: fs/aio.c:691
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81307810-ffffffff8130785a: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81328e10-ffffffff81328e55: aio_nr_sub (STB_LOCAL)
ffffffff8132d032-ffffffff8132d050: aio_nr_sub.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133bab0)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8133bab0-ffffffff8133bafa: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81375d90)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81375d90-ffffffff81375ddd: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81383c60)
Location: fs/aio.c:690
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81383c60-ffffffff81383cad: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138b360)
Location: fs/aio.c:687
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8138b360-ffffffff8138b3ad: aio_nr_sub (STB_LOCAL)
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
In fs/aio.c (ffffffff813db7b9)
Location: fs/aio.c:688
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff81461611)
Location: fs/aio.c:714
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff814f15d1)
Location: fs/aio.c:718
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff81528b71)
Location: fs/aio.c:716
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155dc71)
Location: fs/aio.c:726
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
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
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fa948)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffff8000103fa948-ffff8000103faa14: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05ce0d8)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
```
**Symbols:**

```
c05ce0d8-c05ce154: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c0000000005028d0)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
c0000000005028d0-c0000000005029b4: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aa282)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
```
**Symbols:**

```
ffffffe0002aa282-ffffffe0002aa31c: aio_nr_sub (STB_LOCAL)
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
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81334090)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81334090-ffffffff813340da: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81324bb0)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81324bb0-ffffffff81324bfa: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331b60)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81331b60-ffffffff81331baa: aio_nr_sub (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aio_nr_sub(unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81343730)
Location: fs/aio.c:688
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81343730-ffffffff81343778: aio_nr_sub (STB_LOCAL)
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
