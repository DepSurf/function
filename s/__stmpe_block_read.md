# Function: <code>__stmpe_block_read</code>

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
int __stmpe_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092eea8)
Location: drivers/mfd/stmpe.c:97
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
  - drivers/mfd/stmpe.c:stmpe_block_read
```
**Symbols:**

```
ffff80001092eea8-ffff80001092ef24: __stmpe_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __stmpe_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a105bc)
Location: drivers/mfd/stmpe.c:97
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
  - drivers/mfd/stmpe.c:stmpe_block_read
```
**Symbols:**

```
c0a105bc-c0a10610: __stmpe_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __stmpe_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce8c0)
Location: drivers/mfd/stmpe.c:97
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
  - drivers/mfd/stmpe.c:stmpe_block_read
```
**Symbols:**

```
c0000000009ce8c0-c0000000009ce954: __stmpe_block_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __stmpe_block_read(struct stmpe *stmpe, u8 reg, u8 length, u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a5942)
Location: drivers/mfd/stmpe.c:97
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_set_altfunc
  - drivers/mfd/stmpe.c:stmpe_block_read
```
**Symbols:**

```
ffffffe0005a5942-ffffffe0005a59a2: __stmpe_block_read (STB_LOCAL)
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
