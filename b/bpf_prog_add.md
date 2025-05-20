# Function: <code>bpf_prog_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180c00)
Location: kernel/bpf/syscall.c:673
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff81180c00-ffffffff81180c30: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118c920)
Location: kernel/bpf/syscall.c:758
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff8118c920-ffffffff8118c950: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191870)
Location: kernel/bpf/syscall.c:845
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff81191870-ffffffff811918a0: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e840)
Location: kernel/bpf/syscall.c:1014
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff8119e840-ffffffff8119e870: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3630)
Location: kernel/bpf/syscall.c:1115
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811b3630-ffffffff811b3662: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1d10)
Location: kernel/bpf/syscall.c:1301
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811c1d10-ffffffff811c1d42: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2360)
Location: kernel/bpf/syscall.c:1438
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811d2360-ffffffff811d2392: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de900)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811de900-ffffffff811de932: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb3d0)
Location: kernel/bpf/syscall.c:1846
Inline: False
```
**Symbols:**

```
ffffffff811fb3d0-ffffffff811fb3e6: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa530)
Location: kernel/bpf/syscall.c:1820
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff811fa530-ffffffff811fa546: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb470)
Location: kernel/bpf/syscall.c:1828
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff811fb470-ffffffff811fb486: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cbb0)
Location: kernel/bpf/syscall.c:1922
Inline: False
```
**Symbols:**

```
ffffffff8122cbb0-ffffffff8122cbc6: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126eed0)
Location: kernel/bpf/syscall.c:2168
Inline: False
```
**Symbols:**

```
ffffffff8126eed0-ffffffff8126eef0: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c46d0)
Location: kernel/bpf/syscall.c:2202
Inline: False
```
**Symbols:**

```
ffffffff812c46d0-ffffffff812c46f0: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb6d0)
Location: kernel/bpf/syscall.c:2281
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
```
**Symbols:**

```
ffffffff812eb6d0-ffffffff812eb6f0: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309c20)
Location: kernel/bpf/syscall.c:2321
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
```
**Symbols:**

```
ffffffff81309c20-ffffffff81309c40: bpf_prog_add (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025fea8)
Location: kernel/bpf/syscall.c:1459
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffff80001025fea8-ffff80001025ff40: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0493330)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
c0493330-c0493394: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304c10)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
c000000000304c10-c000000000304c60: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019de08)
Location: kernel/bpf/syscall.c:1459
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffe00019d79a-ffffffe00019d7e0: bpf_prog_add (STB_GLOBAL)
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
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6f20)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811d6f20-ffffffff811d6f52: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9ce0)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811c9ce0-ffffffff811c9d12: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4cf0)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811d4cf0-ffffffff811d4d22: bpf_prog_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prog_add(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3020)
Location: kernel/bpf/syscall.c:1459
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_get
```
**Symbols:**

```
ffffffff811e3020-ffffffff811e3052: bpf_prog_add (STB_GLOBAL)
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
<code>struct bpf_prog *</code> ➡️ <code>void</code>
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
