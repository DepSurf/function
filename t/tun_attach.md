# Function: <code>tun_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ef670)
Location: drivers/net/tun.c:598
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff815ef670-ffffffff815ef836: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164e1e0)
Location: drivers/net/tun.c:621
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8164e1e0-ffffffff8164e470: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167fef0)
Location: drivers/net/tun.c:621
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8167fef0-ffffffff81680180: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816952f0)
Location: drivers/net/tun.c:624
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff816952f0-ffffffff8169558a: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816ffe50)
Location: drivers/net/tun.c:727
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff816ffe50-ffffffff81700192: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173d900)
Location: drivers/net/tun.c:793
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8173d900-ffffffff8173dddf: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81761840)
Location: drivers/net/tun.c:793
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81761840-ffffffff81761d35: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8179f520-ffffffff8179fa41: tun_attach (STB_LOCAL)
ffffffff817a2f15-ffffffff817a2f28: tun_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c37b0)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817c37b0-ffffffff817c3ce0: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8188f0c0)
Location: drivers/net/tun.c:757
Inline: True
```
**Symbols:**

```
ffffffff8188f0c0-ffffffff8188f65d: tun_attach.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8189d440)
Location: drivers/net/tun.c:728
Inline: True
```
**Symbols:**

```
ffffffff8189d440-ffffffff8189d9df: tun_attach.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8187fc90)
Location: drivers/net/tun.c:736
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8187fc90-ffffffff81880212: tun_attach.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:742
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81911500-ffffffff81911ac0: tun_attach.isra.0 (STB_LOCAL)
ffffffff81d10ae7-ffffffff81d10afc: tun_attach.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:751
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81a64400-ffffffff81a649fb: tun_attach.isra.0 (STB_LOCAL)
ffffffff81edb8ba-ffffffff81edb8e4: tun_attach.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:753
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81bef670-ffffffff81befc6b: tun_attach.isra.0 (STB_LOCAL)
ffffffff8209d74f-ffffffff8209d779: tun_attach.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:753
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81c47bf0-ffffffff81c481ef: tun_attach.isra.0 (STB_LOCAL)
ffffffff8211e659-ffffffff8211e683: tun_attach.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:754
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81cfd570-ffffffff81cfdb6f: tun_attach.isra.0 (STB_LOCAL)
ffffffff821ffcac-ffffffff821ffcd6: tun_attach.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffff8000109de318)
Location: drivers/net/tun.c:789
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffff8000109de318-ffff8000109de810: tun_attach.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac31c4)
Location: drivers/net/tun.c:789
Inline: False
```
**Symbols:**

```
c0ac31c4-c0ac365c: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9f3c0)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
c000000000a9f3c0-c000000000a9f9d4: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000628bde)
Location: drivers/net/tun.c:789
Inline: False
```
**Symbols:**

```
ffffffe000628bde-ffffffe000629016: tun_attach (STB_LOCAL)
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
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81788290)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81788290-ffffffff817887c0: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81767be0)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81767be0-ffffffff81768110: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b8630)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817b8630-ffffffff817b8b60: tun_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tun_attach(struct tun_struct *tun, struct file *file, bool skip_filter, bool napi, bool napi_frags, bool publish_tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d1570)
Location: drivers/net/tun.c:789
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817d1570-ffffffff817d1a9e: tun_attach (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool napi</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool napi_frags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool publish_tun</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
