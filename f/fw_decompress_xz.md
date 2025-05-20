# Function: <code>fw_decompress_xz</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffff816f55b0-ffffffff816f5762: fw_decompress_xz (STB_LOCAL)
ffffffff816f6029-ffffffff816f6079: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffff817199b0-ffffffff81719b62: fw_decompress_xz (STB_LOCAL)
ffffffff8171a429-ffffffff8171a479: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:432
Inline: False
```
**Symbols:**

```
ffffffff817d5be0-ffffffff817d5cb5: fw_decompress_xz (STB_LOCAL)
ffffffff817d63f0-ffffffff817d6414: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:453
Inline: False
```
**Symbols:**

```
ffffffff817ea5f0-ffffffff817ea6c5: fw_decompress_xz (STB_LOCAL)
ffffffff81c0f1b2-ffffffff81c0f1d6: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:454
Inline: False
```
**Symbols:**

```
ffffffff817ceb80-ffffffff817ced6c: fw_decompress_xz (STB_LOCAL)
ffffffff81c012f7-ffffffff81c01347: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:455
Inline: False
```
**Symbols:**

```
ffffffff81859290-ffffffff8185947c: fw_decompress_xz (STB_LOCAL)
ffffffff81d04273-ffffffff81d042c3: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:458
Inline: False
```
**Symbols:**

```
ffffffff8199fe40-ffffffff819a000f: fw_decompress_xz (STB_LOCAL)
ffffffff81eccba0-ffffffff81eccbf0: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11950)
Location: drivers/base/firmware_loader/main.c:458
Inline: False
```
**Symbols:**

```
ffffffff81b11950-ffffffff81b11b56: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5fc40)
Location: drivers/base/firmware_loader/main.c:458
Inline: False
```
**Symbols:**

```
ffffffff81b5fc40-ffffffff81b5fe46: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3650)
Location: drivers/base/firmware_loader/main.c:459
Inline: False
```
**Symbols:**

```
ffffffff81bb3650-ffffffff81bb3856: fw_decompress_xz (STB_LOCAL)
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
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d080)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffff80001090d080-ffff80001090d270: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f60fc)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
c09f60fc-c09f62d4: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ad2f0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
c0000000009ad2f0-c0000000009ad594: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591cdc)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffe000591cdc-ffffffe000591e6e: fw_decompress_xz (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffff816dfce0-ffffffff816dfe92: fw_decompress_xz (STB_LOCAL)
ffffffff816e0759-ffffffff816e07a9: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffff816ba320-ffffffff816ba4d2: fw_decompress_xz (STB_LOCAL)
ffffffff816bad99-ffffffff816bade9: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:427
Inline: False
```
**Symbols:**

```
ffffffff81728020-ffffffff817281cd: fw_decompress_xz (STB_LOCAL)
ffffffff81728a99-ffffffff81728ae9: fw_decompress_xz.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
