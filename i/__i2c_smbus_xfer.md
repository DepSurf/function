# Function: <code>__i2c_smbus_xfer</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fdf00)
Location: drivers/i2c/i2c-core-smbus.c:542
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff817fdf00-ffffffff817fe1e0: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183efe0)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffffffff8183efe0-ffffffff8183f321: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff8183f330-ffffffff8183f3a7: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870980)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffffffff81870980-ffffffff81870cc1: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81870cd0-ffffffff81870d47: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819449c0)
Location: drivers/i2c/i2c-core-smbus.c:550
Inline: True
```
**Symbols:**

```
ffffffff819449c0-ffffffff81944d05: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81944d10-ffffffff81944d87: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194aa40)
Location: drivers/i2c/i2c-core-smbus.c:550
Inline: True
```
**Symbols:**

```
ffffffff8194aa40-ffffffff8194ad4c: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff8194ad50-ffffffff8194adc7: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192e580)
Location: drivers/i2c/i2c-core-smbus.c:544
Inline: True
```
**Symbols:**

```
ffffffff8192e580-ffffffff8192e88c: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff8192e890-ffffffff8192e907: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d17b0)
Location: drivers/i2c/i2c-core-smbus.c:552
Inline: True
```
**Symbols:**

```
ffffffff819d17b0-ffffffff819d1abc: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff819d1ac0-ffffffff819d1b37: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33d00)
Location: drivers/i2c/i2c-core-smbus.c:553
Inline: True
```
**Symbols:**

```
ffffffff81b33d00-ffffffff81b34079: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81b34080-ffffffff81b34103: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8cb0)
Location: drivers/i2c/i2c-core-smbus.c:553
Inline: True
```
**Symbols:**

```
ffffffff81cc8cb0-ffffffff81cc904d: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81cc9060-ffffffff81cc90e3: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d309c0)
Location: drivers/i2c/i2c-core-smbus.c:553
Inline: True
```
**Symbols:**

```
ffffffff81d309c0-ffffffff81d30d67: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81d30d80-ffffffff81d30e03: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6970)
Location: drivers/i2c/i2c-core-smbus.c:553
Inline: True
```
**Symbols:**

```
ffffffff81de6970-ffffffff81de6d36: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81de6d50-ffffffff81de6dd3: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4468)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffff800010ab4468-ffff800010ab4824: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffff800010ab4828-ffff800010ab492c: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95628)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
c0b95628-c0b95ab0: __i2c_smbus_xfer.part.0 (STB_LOCAL)
c0b95ab0-c0b95b54: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98580)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
c000000000b98580-c000000000b98a40: __i2c_smbus_xfer.part.0 (STB_LOCAL)
c000000000b98a40-c000000000b98aec: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bba90)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffffffe0006bba90-ffffffe0006bbd8c: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffe0006bbd8c-ffffffe0006bbe2c: __i2c_smbus_xfer (STB_GLOBAL)
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
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81864b10)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffffffff81864b10-ffffffff81864e51: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81864e60-ffffffff81864ed7: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
s32 __i2c_smbus_xfer(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187fd70)
Location: drivers/i2c/i2c-core-smbus.c:543
Inline: True
```
**Symbols:**

```
ffffffff8187fd70-ffffffff8188010b: __i2c_smbus_xfer.part.0 (STB_LOCAL)
ffffffff81880110-ffffffff81880187: __i2c_smbus_xfer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
