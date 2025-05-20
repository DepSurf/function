# Function: <code>i2c_dw_xfer</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726c20)
Location: drivers/i2c/busses/i2c-designware-master.c:411
Inline: False
```
**Symbols:**

```
ffffffff81726c20-ffffffff81726e5c: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81798270)
Location: drivers/i2c/busses/i2c-designware-master.c:411
Inline: False
```
**Symbols:**

```
ffffffff81798270-ffffffff817984ac: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817daf20)
Location: drivers/i2c/busses/i2c-designware-master.c:416
Inline: False
```
**Symbols:**

```
ffffffff817daf20-ffffffff817db173: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81802560)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffff81802560-ffffffff818027b1: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffff81843410-ffffffff81843695: i2c_dw_xfer (STB_LOCAL)
ffffffff81843b8c-ffffffff81843bd4: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffff81874d90-ffffffff81875015: i2c_dw_xfer (STB_LOCAL)
ffffffff818754f8-ffffffff81875540: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:456
Inline: False
```
**Symbols:**

```
ffffffff81949b70-ffffffff81949d4b: i2c_dw_xfer (STB_LOCAL)
ffffffff8194a01f-ffffffff8194a067: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:456
Inline: False
```
**Symbols:**

```
ffffffff8194f840-ffffffff8194fa0e: i2c_dw_xfer (STB_LOCAL)
ffffffff81c250d8-ffffffff81c25120: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:551
Inline: False
```
**Symbols:**

```
ffffffff81933490-ffffffff81933691: i2c_dw_xfer (STB_LOCAL)
ffffffff81c170d2-ffffffff81c1711a: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:551
Inline: False
```
**Symbols:**

```
ffffffff819d6840-ffffffff819d6a63: i2c_dw_xfer (STB_LOCAL)
ffffffff81d25d67-ffffffff81d25dd9: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:551
Inline: False
```
**Symbols:**

```
ffffffff81b393c0-ffffffff81b3956c: i2c_dw_xfer (STB_LOCAL)
ffffffff81ef1af0-ffffffff81ef1b32: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf140)
Location: drivers/i2c/busses/i2c-designware-master.c:551
Inline: False
```
**Symbols:**

```
ffffffff81ccf140-ffffffff81ccf33c: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d371f0)
Location: drivers/i2c/busses/i2c-designware-master.c:626
Inline: False
```
**Symbols:**

```
ffffffff81d371f0-ffffffff81d37406: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded470)
Location: drivers/i2c/busses/i2c-designware-master.c:640
Inline: False
```
**Symbols:**

```
ffffffff81ded470-ffffffff81ded686: i2c_dw_xfer (STB_LOCAL)
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
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9b18)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffff800010ab9b18-ffff800010ab9dc4: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c0b991bc)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
c0b991bc-c0b99488: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d5d0)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
c000000000b9d5d0-c000000000b9d98c: i2c_dw_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bed14)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffe0006bed14-ffffffe0006befa2: i2c_dw_xfer (STB_LOCAL)
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
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffff8186a240-ffffffff8186a4c5: i2c_dw_xfer (STB_LOCAL)
ffffffff8186a9a8-ffffffff8186a9f0: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_dw_xfer(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (0)
Location: drivers/i2c/busses/i2c-designware-master.c:420
Inline: False
```
**Symbols:**

```
ffffffff818841d0-ffffffff81884455: i2c_dw_xfer (STB_LOCAL)
ffffffff81884938-ffffffff81884980: i2c_dw_xfer.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
