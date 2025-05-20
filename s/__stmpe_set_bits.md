# Function: <code>__stmpe_set_bits</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092ec20)
Location: drivers/mfd/stmpe.c:83
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe24xx_enable
  - drivers/mfd/stmpe.c:stmpe1801_enable
  - drivers/mfd/stmpe.c:stmpe1601_enable
  - drivers/mfd/stmpe.c:stmpe811_enable
  - drivers/mfd/stmpe.c:stmpe_set_bits
```
**Symbols:**

```
ffff80001092ec20-ffff80001092ec7c: __stmpe_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a103ec)
Location: drivers/mfd/stmpe.c:83
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe24xx_enable
  - drivers/mfd/stmpe.c:stmpe1801_enable
  - drivers/mfd/stmpe.c:stmpe1601_enable
  - drivers/mfd/stmpe.c:stmpe811_enable
  - drivers/mfd/stmpe.c:stmpe_set_bits
```
**Symbols:**

```
c0a103ec-c0a10438: __stmpe_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce630)
Location: drivers/mfd/stmpe.c:83
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe24xx_enable
  - drivers/mfd/stmpe.c:stmpe1801_enable
  - drivers/mfd/stmpe.c:stmpe1601_enable
  - drivers/mfd/stmpe.c:stmpe811_enable
  - drivers/mfd/stmpe.c:stmpe_set_bits
```
**Symbols:**

```
c0000000009ce630-c0000000009ce6d0: __stmpe_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a570e)
Location: drivers/mfd/stmpe.c:83
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe24xx_enable
  - drivers/mfd/stmpe.c:stmpe1801_enable
  - drivers/mfd/stmpe.c:stmpe1601_enable
  - drivers/mfd/stmpe.c:stmpe811_enable
  - drivers/mfd/stmpe.c:stmpe_set_bits
```
**Symbols:**

```
ffffffe0005a570e-ffffffe0005a576a: __stmpe_set_bits (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
