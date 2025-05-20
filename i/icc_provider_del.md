# Function: <code>icc_provider_del</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dd5c6)
Location: drivers/interconnect/core.c:1006
Inline: True
```
**Symbols:**

```
ffffffff819dd5a0-ffffffff819dd5e9: icc_provider_del.cold (STB_LOCAL)
ffffffff819dbf70-ffffffff819dbfe0: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81c30286)
Location: drivers/interconnect/core.c:1053
Inline: True
```
**Symbols:**

```
ffffffff81c30260-ffffffff81c302a9: icc_provider_del.cold (STB_LOCAL)
ffffffff819db5d0-ffffffff819db640: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81c22564)
Location: drivers/interconnect/core.c:1060
Inline: True
```
**Symbols:**

```
ffffffff81c2253e-ffffffff81c22587: icc_provider_del.cold (STB_LOCAL)
ffffffff819c1880-ffffffff819c18f0: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d34892)
Location: drivers/interconnect/core.c:1063
Inline: True
```
**Symbols:**

```
ffffffff81d3486c-ffffffff81d348b5: icc_provider_del.cold (STB_LOCAL)
ffffffff81a71100-ffffffff81a71170: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:1063
Inline: False
```
**Symbols:**

```
ffffffff81f00c42-ffffffff81f00c82: icc_provider_del.cold (STB_LOCAL)
ffffffff81be2300-ffffffff81be237a: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void icc_provider_del(struct icc_provider *provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8e330)
Location: drivers/interconnect/core.c:1061
Inline: True
```
**Symbols:**

```
ffffffff81d8e330-ffffffff81d8e3f2: icc_provider_del (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
