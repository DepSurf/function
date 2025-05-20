# Function: <code>iterate_bdevs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81249690)
Location: fs/block_dev.c:1831
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff81249690-ffffffff812497be: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81272110)
Location: fs/block_dev.c:1910
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff81272110-ffffffff8127223e: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81285bf0)
Location: fs/block_dev.c:2232
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff81285bf0-ffffffff81285d43: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812932a0)
Location: fs/block_dev.c:2148
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff812932a0-ffffffff812933f1: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b60a0)
Location: fs/block_dev.c:2144
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:sys_sync
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff812b60a0-ffffffff812b61f3: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dddd0)
Location: fs/block_dev.c:2160
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff812dddd0-ffffffff812ddf23: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f33c0)
Location: fs/block_dev.c:2194
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff812f33c0-ffffffff812f3513: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314e30)
Location: fs/block_dev.c:2235
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81314e30-ffffffff81314f86: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327cd0)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81327cd0-ffffffff81327e26: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361a20)
Location: fs/block_dev.c:2231
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81361a20-ffffffff81361b76: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136ecc0)
Location: fs/block_dev.c:1906
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8136ecc0-ffffffff8136ee16: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81375630)
Location: fs/block_dev.c:1915
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81375630-ffffffff81375786: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c50a0)
Location: block/bdev.c:1019
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff815c50a0-ffffffff815c51f9: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e2c48)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffff8000103e2c48-ffff8000103e2e58: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05bae18)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
c05bae18-c05baf70: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e8b30)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
c0000000004e8b30-c0000000004e8de0: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002990c6)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffe0002990c6-ffffffe0002992da: iterate_bdevs (STB_GLOBAL)
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
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813202b0)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff813202b0-ffffffff81320406: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310e50)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81310e50-ffffffff81310fa6: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131dd80)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8131dd80-ffffffff8131ded6: iterate_bdevs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iterate_bdevs(void (*func)(struct block_device *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132fa80)
Location: fs/block_dev.c:2212
Inline: False
Direct callers:
  - fs/sync.c:do_sync_work
  - fs/sync.c:do_sync_work
  - fs/sync.c:ksys_sync
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8132fa80-ffffffff8132fbcd: iterate_bdevs (STB_GLOBAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
