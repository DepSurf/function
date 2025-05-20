# Function: <code>i2c_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81678bc4)
Location: drivers/i2c/i2c-core.c:491
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816d9f36)
Location: drivers/i2c/i2c-core.c:589
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170a020)
Location: drivers/i2c/i2c-core.c:683
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_device_probe
  - drivers/i2c/i2c-core.c:i2c_device_match
```
**Symbols:**

```
ffffffff8170a020-ffffffff8170a06e: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171f915)
Location: drivers/i2c/i2c-core-base.c:83
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8171f870-ffffffff8171f8b4: i2c_match_id.part.24 (STB_LOCAL)
ffffffff8171f8c0-ffffffff8171f8dd: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81790875)
Location: drivers/i2c/i2c-core-base.c:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff817907d0-ffffffff81790814: i2c_match_id.part.26 (STB_LOCAL)
ffffffff81790820-ffffffff8179083d: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d3593)
Location: drivers/i2c/i2c-core-base.c:86
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff817d33c0-ffffffff817d3404: i2c_match_id.part.25 (STB_LOCAL)
ffffffff817d3410-ffffffff817d342d: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fa758)
Location: drivers/i2c/i2c-core-base.c:86
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff817fa590-ffffffff817fa5d4: i2c_match_id.part.28 (STB_LOCAL)
ffffffff817fa5e0-ffffffff817fa5fd: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183b4ad)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8183b2c0-ffffffff8183b307: i2c_match_id.part.0 (STB_LOCAL)
ffffffff8183b310-ffffffff8183b32d: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186ce3d)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8186cc50-ffffffff8186cc97: i2c_match_id.part.0 (STB_LOCAL)
ffffffff8186cca0-ffffffff8186ccbd: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819418c7)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81940910-ffffffff81940961: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81947c95)
Location: drivers/i2c/i2c-core-base.c:79
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81946ce0-ffffffff81946d31: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192b620)
Location: drivers/i2c/i2c-core-base.c:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8192a5e0-ffffffff8192a631: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819ce7fd)
Location: drivers/i2c/i2c-core-base.c:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff819cd780-ffffffff819cd7d1: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b304f6)
Location: drivers/i2c/i2c-core-base.c:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81b2f960-ffffffff81b2f9be: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc47fa)
Location: drivers/i2c/i2c-core-base.c:101
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81cc3e80-ffffffff81cc3ede: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c77a)
Location: drivers/i2c/i2c-core-base.c:102
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
```
**Symbols:**

```
ffffffff81d2b830-ffffffff81d2b896: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de264a)
Location: drivers/i2c/i2c-core-base.c:105
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_client_get_device_id
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_device_match
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
```
**Symbols:**

```
ffffffff81de16f0-ffffffff81de1756: i2c_match_id (STB_GLOBAL)
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
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010aafc98)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffff800010aaf920-ffff800010aaf988: i2c_match_id.part.0 (STB_LOCAL)
ffff800010aaf988-ffff800010aaf9d8: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b917dc)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
c0b91468-c0b914c0: i2c_match_id.part.0 (STB_LOCAL)
c0b914c0-c0b914f0: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b92ea0)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
c000000000b92980-c000000000b92b8c: i2c_match_id.part.0 (STB_LOCAL)
c000000000b92b90-c000000000b92bc8: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b835e)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffe0006b8008-ffffffe0006b8062: i2c_match_id.part.0 (STB_LOCAL)
ffffffe0006b8062-ffffffe0006b80a8: i2c_match_id (STB_GLOBAL)
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
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81860fcd)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff81860de0-ffffffff81860e27: i2c_match_id.part.0 (STB_LOCAL)
ffffffff81860e30-ffffffff81860e4d: i2c_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct i2c_device_id *i2c_match_id(const struct i2c_device_id *id, const struct i2c_client *client);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187c1dd)
Location: drivers/i2c/i2c-core-base.c:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_match
```
**Symbols:**

```
ffffffff8187bff0-ffffffff8187c037: i2c_match_id.part.0 (STB_LOCAL)
ffffffff8187c040-ffffffff8187c05d: i2c_match_id (STB_GLOBAL)
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
