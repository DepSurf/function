# Function: <code>tun_get_iff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815edc85)
Location: drivers/net/tun.c:1750
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164ca55)
Location: drivers/net/tun.c:1859
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167e785)
Location: drivers/net/tun.c:1850
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81693fa0)
Location: drivers/net/tun.c:1895
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81693fa0-ffffffff81693fd4: tun_get_iff.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff816fdfa0)
Location: drivers/net/tun.c:2367
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff816fdfa0-ffffffff816fdfd4: tun_get_iff.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c1b0)
Location: drivers/net/tun.c:2714
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8173c1b0-ffffffff8173c1e4: tun_get_iff.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8175faf0)
Location: drivers/net/tun.c:2876
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8175faf0-ffffffff8175fb24: tun_get_iff.isra.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179c7f0)
Location: drivers/net/tun.c:2875
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8179c7f0-ffffffff8179c824: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c02a0)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817c02a0-ffffffff817c02d4: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81889cd0)
Location: drivers/net/tun.c:2858
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
```
**Symbols:**

```
ffffffff81889cd0-ffffffff81889d07: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2780
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
```
**Symbols:**

```
ffffffff81897ed0-ffffffff81897f8b: tun_get_iff (STB_LOCAL)
ffffffff81c19569-ffffffff81c19581: tun_get_iff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2785
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8187a780-ffffffff8187a83b: tun_get_iff (STB_LOCAL)
ffffffff81c0b3c5-ffffffff81c0b3dd: tun_get_iff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2793
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8190bca0-ffffffff8190bd5b: tun_get_iff (STB_LOCAL)
ffffffff81d10946-ffffffff81d1095e: tun_get_iff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2843
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81a5f6a0-ffffffff81a5f769: tun_get_iff (STB_LOCAL)
ffffffff81edb6fc-ffffffff81edb714: tun_get_iff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81beaaf0)
Location: drivers/net/tun.c:2850
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81beaaf0-ffffffff81beabd1: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c42f40)
Location: drivers/net/tun.c:2871
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81c42f40-ffffffff81c43021: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cf8a60)
Location: drivers/net/tun.c:2883
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81cf8a60-ffffffff81cf8b52: tun_get_iff (STB_LOCAL)
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
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109daa88)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffff8000109daa88-ffff8000109daacc: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac14bc)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
```
**Symbols:**

```
c0ac14bc-c0ac14f8: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9ca60)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
c000000000a9ca60-c000000000a9cab8: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000625802)
Location: drivers/net/tun.c:2879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
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
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81784d70)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81784d70-ffffffff81784da4: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817646c0)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817646c0-ffffffff817646f4: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5120)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817b5120-ffffffff817b5154: tun_get_iff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tun_get_iff(struct tun_struct *tun, struct ifreq *ifr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cf130)
Location: drivers/net/tun.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817cf130-ffffffff817cf164: tun_get_iff (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
