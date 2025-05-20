# Function: <code>tun_set_ebpf</code>

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
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c0f0)
Location: drivers/net/tun.c:2844
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8173c0f0-ffffffff8173c17d: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8175fa30)
Location: drivers/net/tun.c:3007
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8175fa30-ffffffff8175fabd: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179d260)
Location: drivers/net/tun.c:3005
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8179d260-ffffffff8179d2ef: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0d00)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817c0d00-ffffffff817c0d8f: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188a630)
Location: drivers/net/tun.c:2986
Inline: False
```
**Symbols:**

```
ffffffff8188a630-ffffffff8188a6bf: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81898760)
Location: drivers/net/tun.c:2908
Inline: False
```
**Symbols:**

```
ffffffff81898760-ffffffff818987ef: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187aea0)
Location: drivers/net/tun.c:2913
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8187aea0-ffffffff8187af2f: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190c3a0)
Location: drivers/net/tun.c:2921
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8190c3a0-ffffffff8190c42f: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a5ff40)
Location: drivers/net/tun.c:2971
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81a5ff40-ffffffff81a5ffde: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81beb330)
Location: drivers/net/tun.c:2984
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81beb330-ffffffff81beb3ce: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c43770)
Location: drivers/net/tun.c:3005
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81c43770-ffffffff81c4380e: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cf9080)
Location: drivers/net/tun.c:3017
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81cf9080-ffffffff81cf911e: tun_set_ebpf (STB_LOCAL)
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
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dc130)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffff8000109dc130-ffff8000109dc1e0: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac627c)
Location: drivers/net/tun.c:3009
Inline: False
```
**Symbols:**

```
c0ac627c-c0ac6368: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9dcd0)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
c000000000a9dcd0-c000000000a9ddc0: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe0006261fa)
Location: drivers/net/tun.c:3009
Inline: False
```
**Symbols:**

```
ffffffe0006261fa-ffffffe000626268: tun_set_ebpf (STB_LOCAL)
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
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817857d0)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817857d0-ffffffff8178585f: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81765120)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81765120-ffffffff817651af: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5b80)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817b5b80-ffffffff817b5c0f: tun_set_ebpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tun_set_ebpf(struct tun_struct *tun, struct tun_prog **prog_p, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cff20)
Location: drivers/net/tun.c:3009
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817cff20-ffffffff817cffaf: tun_set_ebpf (STB_LOCAL)
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
