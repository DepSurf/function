# Function: <code>__tun_set_ebpf</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173bfa0)
Location: drivers/net/tun.c:2250
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8173bfa0-ffffffff8173c02c: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8175f8e0)
Location: drivers/net/tun.c:2268
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8175f8e0-ffffffff8175f96c: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179d110)
Location: drivers/net/tun.c:2263
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8179d110-ffffffff8179d19e: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0bb0)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff817c0bb0-ffffffff817c0c3e: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188b2ed)
Location: drivers/net/tun.c:2240
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8188a390-ffffffff8188a41d: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189948d)
Location: drivers/net/tun.c:2167
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81898490-ffffffff8189851d: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187b86d)
Location: drivers/net/tun.c:2172
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8187ad90-ffffffff8187ae1d: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190cd92)
Location: drivers/net/tun.c:2228
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff8190c290-ffffffff8190c31d: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a61792)
Location: drivers/net/tun.c:2260
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81a5fcb0-ffffffff81a5fd44: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81beca72)
Location: drivers/net/tun.c:2264
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81beb1c0-ffffffff81beb254: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44f72)
Location: drivers/net/tun.c:2278
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81c43600-ffffffff81c43694: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfaad2)
Location: drivers/net/tun.c:2290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81cf88d0-ffffffff81cf8995: __tun_set_ebpf (STB_LOCAL)
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
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dbf90)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffff8000109dbf90-ffff8000109dc09c: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac232c)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
c0ac232c-c0ac23c0: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9da00)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
```
**Symbols:**

```
c000000000a9da00-c000000000a9dae0: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000626082)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffe000626082-ffffffe000626120: __tun_set_ebpf (STB_LOCAL)
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
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81785680)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81785680-ffffffff8178570e: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81764fd0)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff81764fd0-ffffffff8176505e: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5a30)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff817b5a30-ffffffff817b5abe: __tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cfdd0)
Location: drivers/net/tun.c:2267
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_set_ebpf
```
**Symbols:**

```
ffffffff817cfdd0-ffffffff817cfe5e: __tun_set_ebpf (STB_LOCAL)
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
