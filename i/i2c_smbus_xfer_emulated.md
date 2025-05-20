# Function: <code>i2c_smbus_xfer_emulated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679e90)
Location: drivers/i2c/i2c-core.c:2835
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff81679e90-ffffffff8167a3a6: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816db630)
Location: drivers/i2c/i2c-core.c:3040
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff816db630-ffffffff816dbb1c: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170b970)
Location: drivers/i2c/i2c-core.c:3328
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff8170b970-ffffffff8170be5c: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81722920)
Location: drivers/i2c/i2c-core-smbus.c:295
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff81722920-ffffffff81722e67: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81793cf0)
Location: drivers/i2c/i2c-core-smbus.c:296
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff81793cf0-ffffffff8179426a: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d6760)
Location: drivers/i2c/i2c-core-smbus.c:315
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff817d6760-ffffffff817d6dc1: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fd890)
Location: drivers/i2c/i2c-core-smbus.c:315
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-smbus.c:__i2c_smbus_xfer
```
**Symbols:**

```
ffffffff817fd890-ffffffff817fdef9: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff8183e9a0-ffffffff8183efdb: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff8183ffa3-ffffffff81840029: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff81870340-ffffffff8187097b: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81871943-ffffffff818719c8: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff81944310-ffffffff819449b6: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff819459ef-ffffffff81945ab1: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff8194a390-ffffffff8194aa3e: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81c24cc1-ffffffff81c24d83: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff8192dc60-ffffffff8192e578: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81c16d71-ffffffff81c16e2c: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:321
Inline: False
```
**Symbols:**

```
ffffffff819d0e70-ffffffff819d17a4: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81d25a6a-ffffffff81d25b26: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:322
Inline: False
```
**Symbols:**

```
ffffffff81b33310-ffffffff81b33cf3: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81ef17ed-ffffffff81ef1882: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8220)
Location: drivers/i2c/i2c-core-smbus.c:322
Inline: False
```
**Symbols:**

```
ffffffff81cc8220-ffffffff81cc8c94: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d2ffa0)
Location: drivers/i2c/i2c-core-smbus.c:322
Inline: False
```
**Symbols:**

```
ffffffff81d2ffa0-ffffffff81d309a4: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de5f50)
Location: drivers/i2c/i2c-core-smbus.c:322
Inline: False
```
**Symbols:**

```
ffffffff81de5f50-ffffffff81de6954: i2c_smbus_xfer_emulated (STB_LOCAL)
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
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab38d8)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffff800010ab38d8-ffff800010ab3f40: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95078)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
c0b95078-c0b95628: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b97d90)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
c000000000b97d90-c000000000b98578: i2c_smbus_xfer_emulated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bb53c)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffe0006bb53c-ffffffe0006bba90: i2c_smbus_xfer_emulated (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff818644d0-ffffffff81864b0b: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81865ad3-ffffffff81865b58: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
s32 i2c_smbus_xfer_emulated(struct i2c_adapter *adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int size, union i2c_smbus_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (0)
Location: drivers/i2c/i2c-core-smbus.c:313
Inline: False
```
**Symbols:**

```
ffffffff8187f730-ffffffff8187fd6b: i2c_smbus_xfer_emulated (STB_LOCAL)
ffffffff81880d83-ffffffff81880e08: i2c_smbus_xfer_emulated.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
