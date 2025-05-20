# Function: <code>sdio_release_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff816cc080)
Location: drivers/mmc/core/sdio_io.c:43
Inline: True
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816cc080-ffffffff816cc0a4: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8172efd0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: True
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8172efd0-ffffffff8172eff4: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81761560)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81761560-ffffffff8176158e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8177fd90)
Location: drivers/mmc/core/sdio_io.c:45
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8177fd90-ffffffff8177fdae: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff817f6350)
Location: drivers/mmc/core/sdio_io.c:45
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817f6350-ffffffff817f636f: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8183f860)
Location: drivers/mmc/core/sdio_io.c:45
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8183f860-ffffffff8183f87f: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8186b810)
Location: drivers/mmc/core/sdio_io.c:45
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8186b810-ffffffff8186b82f: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_io.c (0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818b0269-ffffffff818b027c: sdio_release_host.cold (STB_LOCAL)
ffffffff818af840-ffffffff818af85f: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818e1cf0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818e1cf0-ffffffff818e1d0e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b4cf0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff819b4cf0-ffffffff819b4d0e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b72a0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff819b72a0-ffffffff819b72be: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8199ba60)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8199ba60-ffffffff8199ba7e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81a48410)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81a48410-ffffffff81a4842e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81bb64a0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81bb64a0-ffffffff81bb64ce: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81d5aee0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81d5aee0-ffffffff81d5af0e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81dc5960)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81dc5960-ffffffff81dc598e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81e7e2a0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81e7e2a0-ffffffff81e7e2ce: sdio_release_host (STB_GLOBAL)
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
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffff800010b3c2f0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffff800010b3c2f0-ffff800010b3c334: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c0c169d4)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c0c169d4-c0c16a18: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c000000000c391d0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c000000000c391d0-c000000000c39220: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffe00071380c)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffe00071380c-ffffffe000713846: sdio_release_host (STB_GLOBAL)
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
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818856b0)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818856b0-ffffffff818856ce: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818d6b50)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818d6b50-ffffffff818d6b6e: sdio_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sdio_release_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818f3670)
Location: drivers/mmc/core/sdio_io.c:43
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818f3670-ffffffff818f368e: sdio_release_host (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
