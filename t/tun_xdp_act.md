# Function: <code>tun_xdp_act</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81760900)
Location: drivers/net/tun.c:1630
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81760900-ffffffff81760a8a: tun_xdp_act.isra.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8179e0f0)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff8179e0f0-ffffffff8179e272: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817c1b80)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff817c1b80-ffffffff817c1d02: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188cab0)
Location: drivers/net/tun.c:1588
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8188cab0-ffffffff8188cc7d: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189ad20)
Location: drivers/net/tun.c:1519
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8189ad20-ffffffff8189aed4: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187d580)
Location: drivers/net/tun.c:1530
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8187d580-ffffffff8187d741: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190ec00)
Location: drivers/net/tun.c:1586
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
```
**Symbols:**

```
ffffffff8190ec00-ffffffff8190edbe: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a62370)
Location: drivers/net/tun.c:1614
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
```
**Symbols:**

```
ffffffff81a62370-ffffffff81a6258f: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81becb10)
Location: drivers/net/tun.c:1617
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
```
**Symbols:**

```
ffffffff81becb10-ffffffff81becd27: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c45010)
Location: drivers/net/tun.c:1623
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
```
**Symbols:**

```
ffffffff81c45010-ffffffff81c45227: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa230)
Location: drivers/net/tun.c:1626
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
```
**Symbols:**

```
ffffffff81cfa230-ffffffff81cfa4b1: tun_xdp_act (STB_LOCAL)
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
In drivers/net/tun.c (ffff8000109dcfe0)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffff8000109dcfe0-ffff8000109dd1c4: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac2fd0)
Location: drivers/net/tun.c:1623
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
c0ac2fd0-c0ac31c4: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9e690)
Location: drivers/net/tun.c:1623
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
c000000000a9e690-c000000000a9e928: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tun_xdp_act(struct tun_struct *tun, struct bpf_prog *xdp_prog, struct xdp_buff *xdp, u32 act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe0006275c0)
Location: drivers/net/tun.c:1623
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffe0006275c0-ffffffe000627754: tun_xdp_act (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81786650)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81786650-ffffffff817867d2: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81765fa0)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81765fa0-ffffffff81766122: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817b6a00)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff817b6a00-ffffffff817b6b82: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817d0c10)
Location: drivers/net/tun.c:1623
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff817d0c10-ffffffff817d0db0: tun_xdp_act.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
