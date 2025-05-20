# Function: <code>spi_unregister_device</code>

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
In drivers/spi/spi.c (ffffffff815e6e3e)
Location: include/linux/spi/spi.h:1119
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816447f0)
Location: drivers/spi/spi.c:618
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff816447f0-ffffffff8164482b: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816758c0)
Location: drivers/spi/spi.c:619
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff816758c0-ffffffff816758fb: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81689fc0)
Location: drivers/spi/spi.c:635
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81689fc0-ffffffff8168a001: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f451e)
Location: drivers/spi/spi.c:639
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff816f4490-ffffffff816f44e9: spi_unregister_device.part.29 (STB_LOCAL)
ffffffff816f44f0-ffffffff816f4507: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81730f7a)
Location: drivers/spi/spi.c:643
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81730ef0-ffffffff81730f49: spi_unregister_device.part.29 (STB_LOCAL)
ffffffff81730f50-ffffffff81730f66: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175396a)
Location: drivers/spi/spi.c:683
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff817538e0-ffffffff81753939: spi_unregister_device.part.31 (STB_LOCAL)
ffffffff81753940-ffffffff81753956: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178f195)
Location: drivers/spi/spi.c:689
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff8178f110-ffffffff8178f168: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff8178f170-ffffffff8178f186: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b2d5a)
Location: drivers/spi/spi.c:690
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff817b2cd0-ffffffff817b2d28: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff817b2d30-ffffffff817b2d46: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187871a)
Location: drivers/spi/spi.c:702
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81878690-ffffffff818786e8: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff818786f0-ffffffff81878706: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81886f8a)
Location: drivers/spi/spi.c:711
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81886f00-ffffffff81886f5b: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81886f60-ffffffff81886f76: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff818697ea)
Location: drivers/spi/spi.c:712
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81869730-ffffffff818697b7: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff818697c0-ffffffff818697d6: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff818f92fa)
Location: drivers/spi/spi.c:771
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff818f9240-ffffffff818f92c7: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff818f92d0-ffffffff818f92e6: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4a735)
Location: drivers/spi/spi.c:740
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81a4a670-ffffffff81a4a6ff: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81a4a700-ffffffff81a4a722: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd1505)
Location: drivers/spi/spi.c:802
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81bd1420-ffffffff81bd14ac: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81bd14c0-ffffffff81bd14e2: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c29175)
Location: drivers/spi/spi.c:803
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81c29090-ffffffff81c2911c: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81c29130-ffffffff81c29152: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdbbb5)
Location: drivers/spi/spi.c:842
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81cdbad0-ffffffff81cdbb5c: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81cdbb70-ffffffff81cdbb92: spi_unregister_device (STB_GLOBAL)
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
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c3ff0)
Location: drivers/spi/spi.c:690
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffff8000109c3ff0-ffff8000109c4094: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf408)
Location: drivers/spi/spi.c:690
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
c0aaf408-c0aaf450: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a85ce0)
Location: drivers/spi/spi.c:690
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
c000000000a85ce0-c000000000a85d58: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000615ffc)
Location: drivers/spi/spi.c:690
Inline: False
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffe000615ffc-ffffffe000616044: spi_unregister_device (STB_GLOBAL)
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
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177783a)
Location: drivers/spi/spi.c:690
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff817777b0-ffffffff81777808: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff81777810-ffffffff81777826: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817575ea)
Location: drivers/spi/spi.c:690
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff81757560-ffffffff817575b8: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff817575c0-ffffffff817575d6: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a7bda)
Location: drivers/spi/spi.c:690
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff817a7b50-ffffffff817a7ba8: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff817a7bb0-ffffffff817a7bc6: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_unregister_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c1a5a)
Location: drivers/spi/spi.c:690
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
Direct callers:
  - drivers/spi/spi.c:__unregister
```
**Symbols:**

```
ffffffff817c19d0-ffffffff817c1a28: spi_unregister_device.part.0 (STB_LOCAL)
ffffffff817c1a30-ffffffff817c1a46: spi_unregister_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
