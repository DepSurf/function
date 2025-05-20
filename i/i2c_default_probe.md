# Function: <code>i2c_default_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a6f0)
Location: drivers/i2c/i2c-core.c:2353
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
**Symbols:**

```
ffffffff8167a6f0-ffffffff8167a821: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dbe60)
Location: drivers/i2c/i2c-core.c:2558
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
**Symbols:**

```
ffffffff816dbe60-ffffffff816dbf82: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c1a0)
Location: drivers/i2c/i2c-core.c:2845
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
**Symbols:**

```
ffffffff8170c1a0-ffffffff8170c2c2: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171f3e0)
Location: drivers/i2c/i2c-core-base.c:2031
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8171f3e0-ffffffff8171f4fc: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81790330)
Location: drivers/i2c/i2c-core-base.c:2055
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff81790330-ffffffff81790455: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d2e40)
Location: drivers/i2c/i2c-core-base.c:2041
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff817d2e40-ffffffff817d2f78: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817f9f80)
Location: drivers/i2c/i2c-core-base.c:2041
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff817f9f80-ffffffff817fa0b8: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2134
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8183acc0-ffffffff8183ade6: i2c_default_probe (STB_LOCAL)
ffffffff8183d8b6-ffffffff8183d8d4: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8186c650-ffffffff8186c776: i2c_default_probe (STB_LOCAL)
ffffffff8186f2a6-ffffffff8186f2c4: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2069
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81940370-ffffffff81940499: i2c_default_probe (STB_LOCAL)
ffffffff819430df-ffffffff819430fd: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2199
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff819464e0-ffffffff81946605: i2c_default_probe (STB_LOCAL)
ffffffff81c24738-ffffffff81c24756: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2259
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81929d20-ffffffff81929e4d: i2c_default_probe (STB_LOCAL)
ffffffff81c167f5-ffffffff81c16813: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2260
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff819ccea0-ffffffff819ccfcd: i2c_default_probe (STB_LOCAL)
ffffffff81d254e0-ffffffff81d254fe: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2263
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81b2eeb0-ffffffff81b2f01b: i2c_default_probe (STB_LOCAL)
ffffffff81ef139c-ffffffff81ef13b9: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2cb0)
Location: drivers/i2c/i2c-core-base.c:2271
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81cc2cb0-ffffffff81cc2e2c: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a7d0)
Location: drivers/i2c/i2c-core-base.c:2384
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81d2a7d0-ffffffff81d2a94c: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de0690)
Location: drivers/i2c/i2c-core-base.c:2402
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81de0690-ffffffff81de080c: i2c_default_probe (STB_LOCAL)
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
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aaf1b0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffff800010aaf1b0-ffff800010aaf2b0: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b90d3c)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
c0b90d3c-c0b90e40: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b91de0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
c000000000b91de0-c000000000b91f30: i2c_default_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b784a)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffe0006b784a-ffffffe0006b7904: i2c_default_probe (STB_LOCAL)
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
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff818607e0-ffffffff81860906: i2c_default_probe (STB_LOCAL)
ffffffff81863436-ffffffff81863454: i2c_default_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_default_probe(struct i2c_adapter *adap, short unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8187b9f0-ffffffff8187bb16: i2c_default_probe (STB_LOCAL)
ffffffff8187e696-ffffffff8187e6b4: i2c_default_probe.cold (STB_LOCAL)
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
