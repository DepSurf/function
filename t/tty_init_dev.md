# Function: <code>tty_init_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e3a30)
Location: drivers/tty/tty_io.c:1506
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814e3a30-ffffffff814e3bcf: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534d90)
Location: drivers/tty/tty_io.c:1512
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81534d90-ffffffff81534f45: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815614c0)
Location: drivers/tty/tty_io.c:1512
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff815614c0-ffffffff81561675: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815750a0)
Location: drivers/tty/tty_io.c:1280
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
```
**Symbols:**

```
ffffffff815750a0-ffffffff8157524e: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d9890)
Location: drivers/tty/tty_io.c:1292
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff815d9890-ffffffff815d9a7c: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1310
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81613350-ffffffff81613384: tty_init_dev.cold.40 (STB_LOCAL)
ffffffff81612830-ffffffff816129f2: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162f90a)
Location: drivers/tty/tty_io.c:1315
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81630404-ffffffff81630438: tty_init_dev.cold.39 (STB_LOCAL)
ffffffff8162f8d0-ffffffff8162fa92: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816637fa)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81664366-ffffffff8166439b: tty_init_dev.cold (STB_LOCAL)
ffffffff816637c0-ffffffff81663982: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81685e6a)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff816869ad-ffffffff816869e2: tty_init_dev.cold (STB_LOCAL)
ffffffff81685e30-ffffffff81685ff2: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737dce)
Location: drivers/tty/tty_io.c:1318
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817378a0-ffffffff81737acb: tty_init_dev.part.0 (STB_LOCAL)
ffffffff817387eb-ffffffff81738821: tty_init_dev.part.0.cold (STB_LOCAL)
ffffffff81737ad0-ffffffff81737b0c: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8175418e)
Location: drivers/tty/tty_io.c:1399
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81753c60-ffffffff81753e8b: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81c076b3-ffffffff81c076e9: tty_init_dev.part.0.cold (STB_LOCAL)
ffffffff81753e90-ffffffff81753ecc: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8173823f)
Location: drivers/tty/tty_io.c:1414
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81737b00-ffffffff81737d2b: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81bf931d-ffffffff81bf9353: tty_init_dev.part.0.cold (STB_LOCAL)
ffffffff81737d30-ffffffff81737d6c: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b8cdf)
Location: drivers/tty/tty_io.c:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817b85a0-ffffffff817b87cb: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81cf8b0a-ffffffff81cf8b40: tty_init_dev.part.0.cold (STB_LOCAL)
ffffffff817b87d0-ffffffff817b880c: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f4e16)
Location: drivers/tty/tty_io.c:1396
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff818f4520-ffffffff818f476b: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81ec0c1f-ffffffff81ec0c53: tty_init_dev.part.0.cold (STB_LOCAL)
ffffffff818f4770-ffffffff818f47b2: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4d435)
Location: drivers/tty/tty_io.c:1392
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a4cd90-ffffffff81a4d00f: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81a4d020-ffffffff81a4d062: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a97733)
Location: drivers/tty/tty_io.c:1401
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a97080-ffffffff81a97303: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81a97320-ffffffff81a97362: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81aea171)
Location: drivers/tty/tty_io.c:1399
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81ae9aa0-ffffffff81ae9d13: tty_init_dev.part.0 (STB_LOCAL)
ffffffff81ae9d30-ffffffff81ae9d72: tty_init_dev (STB_GLOBAL)
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
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010853830)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffff800010853830-ffff800010853a10: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095e194)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c095e194-c095e36c: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f2c30)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c0000000008f2c30-c0000000008f2ec4: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe0005300ea)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffe0005300ea-ffffffe00053029a: tty_init_dev (STB_GLOBAL)
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
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164b8ea)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8164c42d-ffffffff8164c462: tty_init_dev.cold (STB_LOCAL)
ffffffff8164b8b0-ffffffff8164ba72: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bd3a)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff8162c87d-ffffffff8162c8b2: tty_init_dev.cold (STB_LOCAL)
ffffffff8162bd00-ffffffff8162bec2: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81679caa)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8167a7ed-ffffffff8167a822: tty_init_dev.cold (STB_LOCAL)
ffffffff81679c70-ffffffff81679e32: tty_init_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_struct *tty_init_dev(struct tty_driver *driver, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8169430a)
Location: drivers/tty/tty_io.c:1317
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81694e55-ffffffff81694e8a: tty_init_dev.cold (STB_LOCAL)
ffffffff816942d0-ffffffff81694492: tty_init_dev (STB_GLOBAL)
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
