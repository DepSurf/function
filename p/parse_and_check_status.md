# Function: <code>parse_and_check_status</code>

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
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145e7a0)
Location: block/sed-opal.c:944
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8145e7a0-ffffffff8145eba2: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8148a660)
Location: block/sed-opal.c:956
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8148a660-ffffffff8148aa62: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bf2b0)
Location: block/sed-opal.c:973
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff814bf2b0-ffffffff814bf69f: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d3740)
Location: block/sed-opal.c:973
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff814d3740-ffffffff814d3b2d: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81500560)
Location: block/sed-opal.c:1004
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81500560-ffffffff81500937: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151e4c0)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8151e4c0-ffffffff8151e866: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157f85b)
Location: block/sed-opal.c:1005
Inline: True
Inline callers:
  - block/sed-opal.c:end_session_cont
Direct callers:
  - block/sed-opal.c:get_active_key_cont
```
**Symbols:**

```
ffffffff8157cf50-ffffffff8157cfb4: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159c89b)
Location: block/sed-opal.c:1005
Inline: True
Inline callers:
  - block/sed-opal.c:end_session_cont
Direct callers:
  - block/sed-opal.c:get_active_key_cont
```
**Symbols:**

```
ffffffff81599f90-ffffffff81599ff4: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0be0)
Location: block/sed-opal.c:1005
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff815a0be0-ffffffff815a0ce0: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609420)
Location: block/sed-opal.c:1005
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81609420-ffffffff8160951d: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bd330)
Location: block/sed-opal.c:1005
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff816bd330-ffffffff816bd445: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177dfb0)
Location: block/sed-opal.c:1045
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8177dfb0-ffffffff8177e0b6: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bdb10)
Location: block/sed-opal.c:1053
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff817bdb10-ffffffff817bdc16: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802270)
Location: block/sed-opal.c:1170
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81802270-ffffffff81802376: parse_and_check_status (STB_LOCAL)
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
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010627310)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffff800010627310-ffff80001062745c: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cee6c)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
c07cee6c-c07cf2d4: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c8640)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
c0000000007c8640-c0000000007c8b98: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000458c00)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffe000458c00-ffffffe000458ff4: parse_and_check_status (STB_LOCAL)
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
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81516aa0)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81516aa0-ffffffff81516e46: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81506db0)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81506db0-ffffffff81507156: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81512b30)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81512b30-ffffffff81512ed6: parse_and_check_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_and_check_status(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152c2f0)
Location: block/sed-opal.c:1003
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8152c2f0-ffffffff8152c696: parse_and_check_status (STB_LOCAL)
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
