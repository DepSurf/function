# Function: <code>soc_device_match_attr</code>

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
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int soc_device_match_attr(const struct soc_device_attribute *attr, const struct soc_device_attribute *match);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81b78430)
Location: drivers/base/soc.c:211
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_device_match
  - drivers/base/soc.c:soc_device_match_one
```
**Symbols:**

```
ffffffff81b78430-ffffffff81b784e0: soc_device_match_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int soc_device_match_attr(const struct soc_device_attribute *attr, const struct soc_device_attribute *match);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81bcc230)
Location: drivers/base/soc.c:211
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_device_match
  - drivers/base/soc.c:soc_device_match_one
```
**Symbols:**

```
ffffffff81bcc230-ffffffff81bcc2e0: soc_device_match_attr (STB_LOCAL)
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
int soc_device_match_attr(const struct soc_device_attribute *attr, const struct soc_device_attribute *match);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffff80001091ea28)
Location: drivers/base/soc.c:194
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_device_match_one
```
**Symbols:**

```
ffff80001091ea28-ffff80001091eae0: soc_device_match_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int soc_device_match_attr(const struct soc_device_attribute *attr, const struct soc_device_attribute *match);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0a03d58)
Location: drivers/base/soc.c:194
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_device_match_one
```
**Symbols:**

```
c0a03d58-c0a03e10: soc_device_match_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int soc_device_match_attr(const struct soc_device_attribute *attr, const struct soc_device_attribute *match);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0000000009c38a0)
Location: drivers/base/soc.c:194
Inline: True
Direct callers:
  - drivers/base/soc.c:soc_device_match_one
```
**Symbols:**

```
c0000000009c38a0-c0000000009c39c0: soc_device_match_attr (STB_LOCAL)
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
