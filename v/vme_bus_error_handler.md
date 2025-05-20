# Function: <code>vme_bus_error_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f15b0)
Location: drivers/vme/vme.c:1026
Inline: True
```
**Symbols:**

```
ffffffff816f15b0-ffffffff816f163f: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817565f0)
Location: drivers/vme/vme.c:1026
Inline: True
```
**Symbols:**

```
ffffffff817565f0-ffffffff8175667c: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81782bd0)
Location: drivers/vme/vme.c:1029
Inline: True
```
**Symbols:**

```
ffffffff81782bd0-ffffffff81782c5c: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a1950)
Location: drivers/vme/vme.c:1281
Inline: True
```
**Symbols:**

```
ffffffff817a1950-ffffffff817a19e0: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818a70)
Location: drivers/vme/vme.c:1258
Inline: True
```
**Symbols:**

```
ffffffff81818a70-ffffffff81818b00: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff818622e0)
Location: drivers/vme/vme.c:1258
Inline: True
```
**Symbols:**

```
ffffffff818622e0-ffffffff8186236e: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81881ad0)
Location: drivers/vme/vme.c:1258
Inline: True
```
**Symbols:**

```
ffffffff81881ad0-ffffffff81881b5e: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff818ccc4d)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff818ccc4d-ffffffff818ccc65: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff818cc0c0-ffffffff818cc144: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff818ff03d)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff818ff03d-ffffffff818ff055: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff818fe4b0-ffffffff818fe534: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1254
Inline: False
```
**Symbols:**

```
ffffffff819d5d00-ffffffff819d5d18: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff819d4ec0-ffffffff819d4f44: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81c2fcea-ffffffff81c2fd02: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff819d4a40-ffffffff819d4ac4: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81c21fb2-ffffffff81c21fcb: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff819b9d00-ffffffff819b9d7f: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81d33d17-ffffffff81d33d30: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff81a68df0-ffffffff81a68e6f: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81f000c9-ffffffff81f000f3: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff81bda5d0-ffffffff81bda654: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6c280)
Location: drivers/staging/vme_user/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81d6c280-ffffffff81d6c326: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd9620)
Location: drivers/staging/vme_user/vme.c:1245
Inline: False
```
**Symbols:**

```
ffffffff81dd9620-ffffffff81dd96c6: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e8fae0)
Location: drivers/staging/vme_user/vme.c:1213
Inline: False
```
**Symbols:**

```
ffffffff81e8fae0-ffffffff81e8fb86: vme_bus_error_handler (STB_GLOBAL)
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
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8e3b8)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffff800010b8e3b8-ffff800010b8e4a4: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c7874c)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
c0c7874c-c0c78830: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6c750)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
c000000000c6c750-c000000000c6c848: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe00073419e)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffe00073419e-ffffffe000734248: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff818a036d)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff818a036d-ffffffff818a0385: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff8189f7e0-ffffffff8189f864: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff8185badd)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff8185badd-ffffffff8185baf5: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff8185af50-ffffffff8185afd4: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff818efa5d)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff818efa5d-ffffffff818efa75: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff818eeed0-ffffffff818eef54: vme_bus_error_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vme_bus_error_handler(struct vme_bridge *bridge, long long unsigned int address, int am);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (ffffffff81910b35)
Location: drivers/vme/vme.c:1254
Inline: True
```
**Symbols:**

```
ffffffff81910b35-ffffffff81910b4d: vme_bus_error_handler.cold (STB_LOCAL)
ffffffff819100c0-ffffffff81910144: vme_bus_error_handler (STB_GLOBAL)
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
