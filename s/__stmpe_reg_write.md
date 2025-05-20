# Function: <code>__stmpe_reg_write</code>

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
int __stmpe_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092eaa8)
Location: drivers/mfd/stmpe.c:70
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_reg_write
  - drivers/mfd/stmpe.c:__stmpe_set_bits
```
**Symbols:**

```
ffff80001092eaa8-ffff80001092eb1c: __stmpe_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __stmpe_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a102c8)
Location: drivers/mfd/stmpe.c:70
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_reg_write
  - drivers/mfd/stmpe.c:__stmpe_set_bits
```
**Symbols:**

```
c0a102c8-c0a1031c: __stmpe_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __stmpe_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce450)
Location: drivers/mfd/stmpe.c:70
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_reg_write
  - drivers/mfd/stmpe.c:__stmpe_set_bits
```
**Symbols:**

```
c0000000009ce450-c0000000009ce4e4: __stmpe_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __stmpe_reg_write(struct stmpe *stmpe, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a55d2)
Location: drivers/mfd/stmpe.c:70
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_reg_write
  - drivers/mfd/stmpe.c:__stmpe_set_bits
```
**Symbols:**

```
ffffffe0005a55d2-ffffffe0005a562a: __stmpe_reg_write (STB_LOCAL)
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
