# Function: <code>xdp_do_flush_map</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864860)
Location: net/core/filter.c:2566
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81864860-ffffffff818648a4: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1a00)
Location: net/core/filter.c:3201
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818b1a00-ffffffff818b1a52: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6430)
Location: net/core/filter.c:3415
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818d6430-ffffffff818d6482: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923c10)
Location: net/core/filter.c:3548
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81923c10-ffffffff81923c63: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81955f10)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81955f10-ffffffff81955f68: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bffb60)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffff800010bffb60-ffff800010bffbd8: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d11428)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c0d11428-c0d114bc: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cddcc0)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c000000000cddcc0-c000000000cddd90: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000779622)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffe000779622-ffffffe0007796a8: xdp_do_flush_map (STB_GLOBAL)
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
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5ee0)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818f5ee0-ffffffff818f5f38: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818afd10)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818afd10-ffffffff818afd68: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81946f10)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81946f10-ffffffff81946f68: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_do_flush_map();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968820)
Location: net/core/filter.c:3551
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81968820-ffffffff81968878: xdp_do_flush_map (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
