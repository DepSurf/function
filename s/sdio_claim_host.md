# Function: <code>sdio_claim_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff816cc050)
Location: drivers/mmc/core/sdio_io.c:27
Inline: True
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff816cc050-ffffffff816cc076: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8172efa0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: True
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8172efa0-ffffffff8172efc6: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81761530)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81761530-ffffffff81761560: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8177fd70)
Location: drivers/mmc/core/sdio_io.c:29
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8177fd70-ffffffff8177fd90: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff817f6320)
Location: drivers/mmc/core/sdio_io.c:29
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff817f6320-ffffffff817f6343: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8183f830)
Location: drivers/mmc/core/sdio_io.c:29
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8183f830-ffffffff8183f853: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8186b7e0)
Location: drivers/mmc/core/sdio_io.c:29
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8186b7e0-ffffffff8186b803: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_io.c (0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818b0256-ffffffff818b0269: sdio_claim_host.cold (STB_LOCAL)
ffffffff818af810-ffffffff818af833: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818e1cc0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818e1cc0-ffffffff818e1ce2: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b4cc0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff819b4cc0-ffffffff819b4ce2: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b7270)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff819b7270-ffffffff819b7292: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8199ba30)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff8199ba30-ffffffff8199ba52: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81a483e0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81a483e0-ffffffff81a48402: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81bb6460)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81bb6460-ffffffff81bb649a: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81d5ae90)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81d5ae90-ffffffff81d5aeca: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81dc5910)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81dc5910-ffffffff81dc594a: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81e7e250)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81e7e250-ffffffff81e7e28a: sdio_claim_host (STB_GLOBAL)
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
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffff800010b3c2a0)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffff800010b3c2a0-ffff800010b3c2ec: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c0c16988)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c0c16988-c0c169d4: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c000000000c39170)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
c000000000c39170-c000000000c391c8: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffe0007137ce)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffe0007137ce-ffffffe00071380c: sdio_claim_host (STB_GLOBAL)
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
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81885680)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff81885680-ffffffff818856a2: sdio_claim_host (STB_GLOBAL)
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
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818d6b20)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818d6b20-ffffffff818d6b42: sdio_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sdio_claim_host(struct sdio_func *func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818f3640)
Location: drivers/mmc/core/sdio_io.c:27
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff818f3640-ffffffff818f3662: sdio_claim_host (STB_GLOBAL)
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
