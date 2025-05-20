# Function: <code>soc_device_unregister</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void soc_device_unregister(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81b782e0)
Location: drivers/base/soc.c:188
Inline: False
```
**Symbols:**

```
ffffffff81b782e0-ffffffff81b78301: soc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void soc_device_unregister(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81bcc0e0)
Location: drivers/base/soc.c:188
Inline: False
```
**Symbols:**

```
ffffffff81bcc0e0-ffffffff81bcc101: soc_device_unregister (STB_GLOBAL)
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
void soc_device_unregister(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffff80001091e790)
Location: drivers/base/soc.c:170
Inline: False
Direct callers:
  - drivers/soc/fsl/guts.c:fsl_guts_remove
```
**Symbols:**

```
ffff80001091e790-ffff80001091e7d8: soc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void soc_device_unregister(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0a03b1c)
Location: drivers/base/soc.c:170
Inline: False
Direct callers:
  - drivers/soc/fsl/guts.c:fsl_guts_remove
```
**Symbols:**

```
c0a03b1c-c0a03b60: soc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void soc_device_unregister(struct soc_device *soc_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0000000009c3740)
Location: drivers/base/soc.c:170
Inline: False
Direct callers:
  - drivers/soc/fsl/guts.c:fsl_guts_remove
```
**Symbols:**

```
c0000000009c3740-c0000000009c37a4: soc_device_unregister (STB_GLOBAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
