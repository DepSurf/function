# Function: <code>pci_do_find_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143a8f0)
Location: drivers/pci/search.c:106
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_do_find_bus
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff8143a8f0-ffffffff8143a941: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486820)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81486820-ffffffff81486871: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a7fd0)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff814a7fd0-ffffffff814a8021: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b1fc0)
Location: drivers/pci/search.c:114
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff814b1fc0-ffffffff814b2010: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f16b0)
Location: drivers/pci/search.c:114
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff814f16b0-ffffffff814f1700: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521940)
Location: drivers/pci/search.c:115
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81521940-ffffffff8152198f: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537770)
Location: drivers/pci/search.c:115
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81537770-ffffffff815377bf: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81567100)
Location: drivers/pci/search.c:111
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81567100-ffffffff8156714d: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588460)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81588460-ffffffff815884ad: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f7ee)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff8162f4d0-ffffffff8162f7a8: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654e7e)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff81654b60-ffffffff81654e38: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816379dc)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff81637690-ffffffff81637976: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7c6c)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff816a7920-ffffffff816a7c06: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca789)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff817ca390-ffffffff817ca6e3: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e8279)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff818e7e70-ffffffff818e81c3: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b889)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff8192b480-ffffffff8192b7d1: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff819741d9)
Location: drivers/pci/search.c:116
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_find_bus
Direct callers:
  - drivers/pci/search.c:pci_find_bus
```
**Symbols:**

```
ffffffff81973dd0-ffffffff81974121: pci_do_find_bus (STB_LOCAL)
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
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ec8e8)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffff8000106ec8e8-ffff8000106ec968: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887b34)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
c0887b34-c0887b94: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0000000008685f0)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
c0000000008685f0-c00000000086869c: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1840)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffe0004c1840-ffffffe0004c1898: pci_do_find_bus (STB_LOCAL)
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
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c2f0)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff8157c2f0-ffffffff8157c33d: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b0c0)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff8156b0c0-ffffffff8156b10d: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c1b0)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff8157c1b0-ffffffff8157c1fd: pci_do_find_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_bus *pci_do_find_bus(struct pci_bus *bus, unsigned char busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596660)
Location: drivers/pci/search.c:110
Inline: False
Direct callers:
  - drivers/pci/search.c:pci_find_bus
  - drivers/pci/search.c:pci_do_find_bus
```
**Symbols:**

```
ffffffff81596660-ffffffff815966ad: pci_do_find_bus (STB_LOCAL)
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
