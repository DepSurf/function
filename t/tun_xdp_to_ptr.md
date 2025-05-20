# Function: <code>tun_xdp_to_ptr</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173cd69)
Location: drivers/net/tun.c:262
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_xmit
```
**Symbols:**

```
ffffffff8173b6b0-ffffffff8173b6c2: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81760809)
Location: drivers/net/tun.c:268
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_xmit
```
**Symbols:**

```
ffffffff8175ee70-ffffffff8175ee82: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179c570)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff8179c570-ffffffff8179c582: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0020)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff817c0020-ffffffff817c0032: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81889ac0)
Location: drivers/net/tun.c:228
Inline: True
```
**Symbols:**

```
ffffffff81889ac0-ffffffff81889ad2: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189abf6)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187d4dd)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8190eb3a)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a61036)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bec326)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44816)
Location: include/linux/if_tun.h:34
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa0fa)
Location: include/linux/if_tun.h:34
Inline: True
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
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109da6e8)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffff8000109da6e8-ffff8000109da710: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac11dc)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
c0ac11dc-c0ac11f8: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9c700)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
c000000000a9c700-c000000000a9c710: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe00062545a)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffe00062545a-ffffffe00062547e: tun_xdp_to_ptr (STB_GLOBAL)
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
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81784af0)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff81784af0-ffffffff81784b02: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81764440)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff81764440-ffffffff81764452: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b4ea0)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff817b4ea0-ffffffff817b4eb2: tun_xdp_to_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *tun_xdp_to_ptr(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817cee70)
Location: drivers/net/tun.c:258
Inline: True
```
**Symbols:**

```
ffffffff817cee70-ffffffff817cee82: tun_xdp_to_ptr (STB_GLOBAL)
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
