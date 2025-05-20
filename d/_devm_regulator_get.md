# Function: <code>_devm_regulator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff814de890)
Location: drivers/regulator/devres.c:33
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_bulk_get
```
**Symbols:**

```
ffffffff814de890-ffffffff814de94d: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8152fa10)
Location: drivers/regulator/devres.c:33
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8152fa10-ffffffff8152fad7: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8155c070)
Location: drivers/regulator/devres.c:33
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_bulk_get
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
```
**Symbols:**

```
ffffffff8155c070-ffffffff8155c137: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81570b20)
Location: drivers/regulator/devres.c:27
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81570b20-ffffffff81570bb2: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815d4dc0)
Location: drivers/regulator/devres.c:27
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff815d4dc0-ffffffff815d4e52: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8160dbc0)
Location: drivers/regulator/devres.c:27
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8160dbc0-ffffffff8160dc51: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8162a6e0)
Location: drivers/regulator/devres.c:27
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8162a6e0-ffffffff8162a771: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8165e2b0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8165e2b0-ffffffff8165e335: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81680a20)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81680a20-ffffffff81680aa5: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731ba0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81731ba0-ffffffff81731c25: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8174dcc0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8174dcc0-ffffffff8174dd45: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731840)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81731840-ffffffff817318c5: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817b18f0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff817b18f0-ffffffff817b197c: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff818ed070)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff818ed070-ffffffff818ed108: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44520)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81a44520-ffffffff81a445b8: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8e6d0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81a8e6d0-ffffffff81a8e768: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae0f40)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:_devm_regulator_get_enable
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81ae0f40-ffffffff81ae0fd8: _devm_regulator_get (STB_LOCAL)
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
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffff80001084a648)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffff80001084a648-ffff80001084a6e0: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0953c84)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
c0953c84-c0953d0c: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0000000008e7e10)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
c0000000008e7e10-c0000000008e7ee8: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffe00052a358)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffe00052a358-ffffffe00052a3de: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff816464a0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff816464a0-ffffffff81646525: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81626900)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81626900-ffffffff81626985: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81674860)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff81674860-ffffffff816748e5: _devm_regulator_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct regulator *_devm_regulator_get(struct device *dev, const char *id, int get_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8168eec0)
Location: drivers/regulator/devres.c:22
Inline: False
Direct callers:
  - drivers/regulator/devres.c:devm_regulator_get_optional
  - drivers/regulator/devres.c:devm_regulator_get_exclusive
  - drivers/regulator/devres.c:devm_regulator_get
```
**Symbols:**

```
ffffffff8168eec0-ffffffff8168ef45: _devm_regulator_get (STB_LOCAL)
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
