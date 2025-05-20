# Function: <code>kthread_worker_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0a40)
Location: kernel/kthread.c:577
Inline: False
```
**Symbols:**

```
ffffffff810a0a40-ffffffff810a0bbe: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a4120)
Location: kernel/kthread.c:577
Inline: False
```
**Symbols:**

```
ffffffff810a4120-ffffffff810a42a6: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a98d0)
Location: kernel/kthread.c:604
Inline: False
```
**Symbols:**

```
ffffffff810a98d0-ffffffff810a9a82: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6580)
Location: kernel/kthread.c:609
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810a6580-ffffffff810a6704: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810accf0)
Location: kernel/kthread.c:616
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810accf0-ffffffff810ace7f: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3a30)
Location: kernel/kthread.c:634
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810b3a30-ffffffff810b3beb: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc740)
Location: kernel/kthread.c:636
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810bc740-ffffffff810bc8fb: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810c32be-ffffffff810c32e4: kthread_worker_fn.cold (STB_LOCAL)
ffffffff810c2660-ffffffff810c2820: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9010)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810c9010-ffffffff810c91d5: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1440)
Location: kernel/kthread.c:681
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810d1440-ffffffff810d15f2: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbdf0)
Location: kernel/kthread.c:707
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810cbdf0-ffffffff810cc022: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd740)
Location: kernel/kthread.c:734
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810cd740-ffffffff810cd972: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0930)
Location: kernel/kthread.c:734
Inline: False
```
**Symbols:**

```
ffffffff810e0930-ffffffff810e0b48: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810faa90)
Location: kernel/kthread.c:794
Inline: False
```
**Symbols:**

```
ffffffff810faa90-ffffffff810facdc: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d900)
Location: kernel/kthread.c:795
Inline: False
```
**Symbols:**

```
ffffffff8111d900-ffffffff8111db27: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112aaf0)
Location: kernel/kthread.c:796
Inline: False
```
**Symbols:**

```
ffffffff8112aaf0-ffffffff8112ad17: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135210)
Location: kernel/kthread.c:813
Inline: False
```
**Symbols:**

```
ffffffff81135210-ffffffff81135437: kthread_worker_fn (STB_GLOBAL)
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
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101277c0)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffff8000101277c0-ffff800010127a04: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379e08)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
c0379e08-c037a014: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172c10)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
c000000000172c10-c000000000172ef4: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df968)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffe0000df968-ffffffe0000dfb00: kthread_worker_fn (STB_GLOBAL)
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
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3390)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810c3390-ffffffff810c3555: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1bd0)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810b1bd0-ffffffff810b1d89: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c28e0)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810c28e0-ffffffff810c2aa5: kthread_worker_fn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kthread_worker_fn(void *worker_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca150)
Location: kernel/kthread.c:645
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_kthread_worker_fn
```
**Symbols:**

```
ffffffff810ca150-ffffffff810ca2fa: kthread_worker_fn (STB_GLOBAL)
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
