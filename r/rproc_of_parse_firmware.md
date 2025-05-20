# Function: <code>rproc_of_parse_firmware</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c8b40)
Location: drivers/remoteproc/remoteproc_core.c:1085
Inline: False
```
**Symbols:**

```
ffffffff819c8b40-ffffffff819c8b50: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ada00)
Location: drivers/remoteproc/remoteproc_core.c:1091
Inline: False
```
**Symbols:**

```
ffffffff819ada00-ffffffff819ada10: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5bf60)
Location: drivers/remoteproc/remoteproc_core.c:1107
Inline: False
```
**Symbols:**

```
ffffffff81a5bf60-ffffffff81a5bf70: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcbe90)
Location: drivers/remoteproc/remoteproc_core.c:1103
Inline: False
```
**Symbols:**

```
ffffffff81bcbe90-ffffffff81bcbea4: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d75980)
Location: drivers/remoteproc/remoteproc_core.c:996
Inline: False
```
**Symbols:**

```
ffffffff81d75980-ffffffff81d75994: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de38c0)
Location: drivers/remoteproc/remoteproc_core.c:997
Inline: False
```
**Symbols:**

```
ffffffff81de38c0-ffffffff81de38d4: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_of_parse_firmware(struct device *dev, int index, const char **fw_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e999b0)
Location: drivers/remoteproc/remoteproc_core.c:997
Inline: False
```
**Symbols:**

```
ffffffff81e999b0-ffffffff81e999c4: rproc_of_parse_firmware (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
