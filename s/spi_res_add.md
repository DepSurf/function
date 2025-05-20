# Function: <code>spi_res_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81644a93)
Location: drivers/spi/spi.c:2142
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81644790-ffffffff816447e4: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81675b63)
Location: drivers/spi/spi.c:2169
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81675860-ffffffff816758b4: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168a284)
Location: drivers/spi/spi.c:2333
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81689f80-ffffffff81689fb3: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f3830)
Location: drivers/spi/spi.c:2403
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff816f3830-ffffffff816f3863: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8172e440)
Location: drivers/spi/spi.c:2453
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff8172e440-ffffffff8172e473: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81750c20)
Location: drivers/spi/spi.c:2519
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81750c20-ffffffff81750c53: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2727
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81792693-ffffffff817926ae: spi_res_add.cold (STB_LOCAL)
ffffffff8178e480-ffffffff8178e4c4: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b460c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff817b1fb0-ffffffff817b1fe3: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81879ac9)
Location: drivers/spi/spi.c:2937
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81877d60-ffffffff81877d93: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8188845a)
Location: drivers/spi/spi.c:3026
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81886570-ffffffff818865a3: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186b0ad)
Location: drivers/spi/spi.c:3033
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81868de0-ffffffff81868e13: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fa24c)
Location: drivers/spi/spi.c:3162
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff818f8990-ffffffff818f89c3: spi_res_add (STB_GLOBAL)
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
In drivers/spi/spi.c (ffffffff81a4ac79)
Location: drivers/spi/spi.c:874
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
In drivers/spi/spi.c (ffffffff81bd1db9)
Location: drivers/spi/spi.c:936
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
In drivers/spi/spi.c (ffffffff81c296a7)
Location: drivers/spi/spi.c:937
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
In drivers/spi/spi.c (ffffffff81cdbee7)
Location: drivers/spi/spi.c:976
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
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c3a3c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffff8000109c1d60-ffff8000109c1dd0: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf3a8)
Location: drivers/spi/spi.c:2731
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
c0aaf3a8-c0aaf408: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a82d90)
Location: drivers/spi/spi.c:2731
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
c000000000a82d90-c000000000a82dcc: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000616d3c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffe000615fb0-ffffffe000615ffc: spi_res_add (STB_GLOBAL)
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
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817790ec)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81776a90-ffffffff81776ac3: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81758e9c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff81756840-ffffffff81756873: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a948c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff817a6e30-ffffffff817a6e63: spi_res_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void spi_res_add(struct spi_message *message, void *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c331c)
Location: drivers/spi/spi.c:2731
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
**Symbols:**

```
ffffffff817c0cb0-ffffffff817c0ce3: spi_res_add (STB_GLOBAL)
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
