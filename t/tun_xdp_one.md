# Function: <code>tun_xdp_one</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817635d4)
Location: drivers/net/tun.c:2420
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817a1312)
Location: drivers/net/tun.c:2415
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c62d2)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffff8188d190)
Location: drivers/net/tun.c:2398
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff8188d190-ffffffff8188d5e4: tun_xdp_one.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8189b420)
Location: drivers/net/tun.c:2325
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff8189b420-ffffffff8189b85f: tun_xdp_one.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8187db00)
Location: drivers/net/tun.c:2330
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff8187db00-ffffffff8187df3a: tun_xdp_one.isra.0 (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8190f1d0)
Location: drivers/net/tun.c:2381
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff8190f1d0-ffffffff8190f64e: tun_xdp_one.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tun_xdp_one(struct tun_struct *tun, struct tun_file *tfile, struct xdp_buff *xdp, int *flush, struct tun_page *tpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2413
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81a63930-ffffffff81a63f60: tun_xdp_one (STB_LOCAL)
ffffffff81edb89d-ffffffff81edb8ba: tun_xdp_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tun_xdp_one(struct tun_struct *tun, struct tun_file *tfile, struct xdp_buff *xdp, int *flush, struct tun_page *tpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2417
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81bf2b10-ffffffff81bf3148: tun_xdp_one (STB_LOCAL)
ffffffff8209d7af-ffffffff8209d7cc: tun_xdp_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tun_xdp_one(struct tun_struct *tun, struct tun_file *tfile, struct xdp_buff *xdp, int *flush, struct tun_page *tpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2431
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81c49d40-ffffffff81c4a3bb: tun_xdp_one (STB_LOCAL)
ffffffff8211e683-ffffffff8211e6a0: tun_xdp_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tun_xdp_one(struct tun_struct *tun, struct tun_file *tfile, struct xdp_buff *xdp, int *flush, struct tun_page *tpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2443
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
ffffffff81cff6d0-ffffffff81cffd3e: tun_xdp_one (STB_LOCAL)
ffffffff821ffcd6-ffffffff821ffcf3: tun_xdp_one.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109e13fc)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tun_xdp_one(struct tun_struct *tun, struct tun_file *tfile, struct xdp_buff *xdp, int *flush, struct tun_page *tpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac6520)
Location: drivers/net/tun.c:2419
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
```
**Symbols:**

```
c0ac6520-c0ac6bd8: tun_xdp_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa30ec)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
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
In drivers/net/tun.c (ffffffe00062af26)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8178adb2)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176a702)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817bb152)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d4188)
Location: drivers/net/tun.c:2419
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
