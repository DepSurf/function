# Function: <code>i2c_block_write</code>

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
int i2c_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffff8000109300f8)
Location: drivers/mfd/stmpe-i2c.c:41
Inline: False
```
**Symbols:**

```
ffff8000109300f8-ffff800010930144: i2c_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c0a1175c)
Location: drivers/mfd/stmpe-i2c.c:41
Inline: False
```
**Symbols:**

```
c0a1175c-c0a1177c: i2c_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (c0000000009d0060)
Location: drivers/mfd/stmpe-i2c.c:41
Inline: False
```
**Symbols:**

```
c0000000009d0060-c0000000009d0098: i2c_block_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_block_write(struct stmpe *stmpe, u8 reg, u8 length, const u8 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe-i2c.c (ffffffe0005a6908)
Location: drivers/mfd/stmpe-i2c.c:41
Inline: False
```
**Symbols:**

```
ffffffe0005a6908-ffffffe0005a694a: i2c_block_write (STB_LOCAL)
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
