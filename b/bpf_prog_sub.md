# Function: <code>bpf_prog_sub</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118ca70)
Location: kernel/bpf/syscall.c:768
Inline: True
```
**Symbols:**

```
ffffffff8118ca70-ffffffff8118ca9d: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191a30)
Location: kernel/bpf/syscall.c:855
Inline: True
```
**Symbols:**

```
ffffffff81191a30-ffffffff81191a4f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e970)
Location: kernel/bpf/syscall.c:1024
Inline: True
```
**Symbols:**

```
ffffffff8119e970-ffffffff8119e98f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3690)
Location: kernel/bpf/syscall.c:1125
Inline: True
```
**Symbols:**

```
ffffffff811b3690-ffffffff811b36af: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1d70)
Location: kernel/bpf/syscall.c:1311
Inline: True
```
**Symbols:**

```
ffffffff811c1d70-ffffffff811c1d8f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6754)
Location: kernel/bpf/syscall.c:1448
Inline: True
```
**Symbols:**

```
ffffffff811d6754-ffffffff811d6767: bpf_prog_sub.cold (STB_LOCAL)
ffffffff811d2650-ffffffff811d266f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de960)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffff811de960-ffffffff811de97f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc360)
Location: kernel/bpf/syscall.c:1852
Inline: True
```
**Symbols:**

```
ffffffff811fc360-ffffffff811fc386: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb4b0)
Location: kernel/bpf/syscall.c:1826
Inline: True
```
**Symbols:**

```
ffffffff811fb4b0-ffffffff811fb4d6: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc1d0)
Location: kernel/bpf/syscall.c:1834
Inline: True
```
**Symbols:**

```
ffffffff811fc1d0-ffffffff811fc1f6: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cd30)
Location: kernel/bpf/syscall.c:1928
Inline: False
```
**Symbols:**

```
ffffffff8122cd30-ffffffff8122cd56: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f0f0)
Location: kernel/bpf/syscall.c:2174
Inline: False
```
**Symbols:**

```
ffffffff8126f0f0-ffffffff8126f12e: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c4970)
Location: kernel/bpf/syscall.c:2208
Inline: False
```
**Symbols:**

```
ffffffff812c4970-ffffffff812c49ae: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eba50)
Location: kernel/bpf/syscall.c:2287
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
```
**Symbols:**

```
ffffffff812eba50-ffffffff812eba8e: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309fa0)
Location: kernel/bpf/syscall.c:2327
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
```
**Symbols:**

```
ffffffff81309fa0-ffffffff81309fde: bpf_prog_sub (STB_GLOBAL)
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
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025fde0)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffff80001025fde0-ffff80001025fe40: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04933b4)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
c04933b4-c049340c: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304940)
Location: kernel/bpf/syscall.c:1469
Inline: False
```
**Symbols:**

```
c000000000304940-c000000000304974: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019db12)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffe00019db12-ffffffe00019db58: bpf_prog_sub (STB_GLOBAL)
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
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6f80)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffff811d6f80-ffffffff811d6f9f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9d40)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffff811c9d40-ffffffff811c9d5f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4d50)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffff811d4d50-ffffffff811d4d6f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_sub(struct bpf_prog *prog, int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3080)
Location: kernel/bpf/syscall.c:1469
Inline: True
```
**Symbols:**

```
ffffffff811e3080-ffffffff811e309f: bpf_prog_sub (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
