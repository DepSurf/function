# Function: <code>elants_i2c_calibrate</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffed0)
Location: drivers/input/touchscreen/elants_i2c.c:234
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff816ffed0-ffffffff816fffc2: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817157e0)
Location: drivers/input/touchscreen/elants_i2c.c:234
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff817157e0-ffffffff817158c2: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786a00)
Location: drivers/input/touchscreen/elants_i2c.c:235
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff81786a00-ffffffff81786ae2: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7ad0)
Location: drivers/input/touchscreen/elants_i2c.c:234
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff817c7ad0-ffffffff817c7bb1: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817ef170)
Location: drivers/input/touchscreen/elants_i2c.c:235
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff817ef170-ffffffff817ef251: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:230
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff8182fcc0-ffffffff8182fd5f: elants_i2c_calibrate (STB_LOCAL)
ffffffff818311b5-ffffffff818311fb: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:230
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff818615f0-ffffffff8186168f: elants_i2c_calibrate (STB_LOCAL)
ffffffff81862ae5-ffffffff81862b2b: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:267
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81935080-ffffffff8193513e: elants_i2c_calibrate (STB_LOCAL)
ffffffff81936241-ffffffff819362ee: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:272
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff8193c0f0-ffffffff8193c1ae: elants_i2c_calibrate (STB_LOCAL)
ffffffff81c23e83-ffffffff81c23f30: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:285
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff8191f680-ffffffff8191f744: elants_i2c_calibrate (STB_LOCAL)
ffffffff81c15ee1-ffffffff81c15f8e: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:298
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff819c2430-ffffffff819c24f4: elants_i2c_calibrate (STB_LOCAL)
ffffffff81d248e4-ffffffff81d24991: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:298
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81b227f0-ffffffff81b228bf: elants_i2c_calibrate (STB_LOCAL)
ffffffff81ef0754-ffffffff81ef0808: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5070)
Location: drivers/input/touchscreen/elants_i2c.c:298
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81cb5070-ffffffff81cb51f1: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c6e0)
Location: drivers/input/touchscreen/elants_i2c.c:298
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81d1c6e0-ffffffff81d1c861: elants_i2c_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2430)
Location: drivers/input/touchscreen/elants_i2c.c:298
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81dd2430-ffffffff81dd25b1: elants_i2c_calibrate (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:230
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff81855780-ffffffff8185581f: elants_i2c_calibrate (STB_LOCAL)
ffffffff81856c75-ffffffff81856cbb: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int elants_i2c_calibrate(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:230
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:calibrate_store
```
**Symbols:**

```
ffffffff818708b0-ffffffff8187094f: elants_i2c_calibrate (STB_LOCAL)
ffffffff81871da5-ffffffff81871deb: elants_i2c_calibrate.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
