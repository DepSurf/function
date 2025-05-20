# Function: <code>i2c_register_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167cde0)
Location: drivers/i2c/i2c-core.c:1526
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_add_adapter
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
```
**Symbols:**

```
ffffffff8167cde0-ffffffff8167d255: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816ddaf0)
Location: drivers/i2c/i2c-core.c:1694
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff816ddaf0-ffffffff816ddfbd: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170de50)
Location: drivers/i2c/i2c-core.c:1972
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff8170de50-ffffffff8170e374: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81721110)
Location: drivers/i2c/i2c-core-base.c:1214
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81721110-ffffffff81721509: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792490)
Location: drivers/i2c/i2c-core-base.c:1231
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81792490-ffffffff8179288f: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1210
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff817d4ea0-ffffffff817d5253: i2c_register_adapter (STB_LOCAL)
ffffffff817d5af5-ffffffff817d5b2d: i2c_register_adapter.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1213
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff817fbff0-ffffffff817fc3c9: i2c_register_adapter (STB_LOCAL)
ffffffff817fcc25-ffffffff817fcc5d: i2c_register_adapter.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1302
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff8183cf40-ffffffff8183d2d2: i2c_register_adapter (STB_LOCAL)
ffffffff8183db4f-ffffffff8183dc2c: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff8186e940-ffffffff8186ecdb: i2c_register_adapter (STB_LOCAL)
ffffffff8186f50e-ffffffff8186f5d2: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1268
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81942960-ffffffff81942cee: i2c_register_adapter (STB_LOCAL)
ffffffff8194353e-ffffffff81943601: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1396
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81948cd0-ffffffff819490ca: i2c_register_adapter (STB_LOCAL)
ffffffff81c24be4-ffffffff81c24caa: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1430
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff8192c650-ffffffff8192c99f: i2c_register_adapter (STB_LOCAL)
ffffffff81c16cd0-ffffffff81c16d5a: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1431
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff819cf810-ffffffff819cfb6b: i2c_register_adapter (STB_LOCAL)
ffffffff81d259b5-ffffffff81d25a53: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1433
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81b31650-ffffffff81b319e3: i2c_register_adapter (STB_LOCAL)
ffffffff81ef173f-ffffffff81ef17d6: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1427
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81cc61a0-ffffffff81cc6597: i2c_register_adapter (STB_LOCAL)
ffffffff820a763f-ffffffff820a7654: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1471
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81d2de30-ffffffff81d2e227: i2c_register_adapter (STB_LOCAL)
ffffffff82128a42-ffffffff82128a57: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1481
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81de3da0-ffffffff81de41d8: i2c_register_adapter (STB_LOCAL)
ffffffff8220a3d4-ffffffff8220a3e9: i2c_register_adapter.cold (STB_LOCAL)
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
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab20f8)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
```
**Symbols:**

```
ffff800010ab20f8-ffff800010ab2568: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b937a8)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
```
**Symbols:**

```
c0b937a8-c0b93c44: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b95810)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
```
**Symbols:**

```
c000000000b95810-c000000000b95e18: i2c_register_adapter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9e2a)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
  - drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter
```
**Symbols:**

```
ffffffe0006b9e2a-ffffffe0006ba256: i2c_register_adapter (STB_LOCAL)
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
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff81862ad0-ffffffff81862e6b: i2c_register_adapter (STB_LOCAL)
ffffffff8186369e-ffffffff81863762: i2c_register_adapter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_register_adapter(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1307
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter
  - drivers/i2c/i2c-core-base.c:i2c_add_adapter
```
**Symbols:**

```
ffffffff8187dd30-ffffffff8187e0cb: i2c_register_adapter (STB_LOCAL)
ffffffff8187e8fe-ffffffff8187e9c2: i2c_register_adapter.cold (STB_LOCAL)
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
