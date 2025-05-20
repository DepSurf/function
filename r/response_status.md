# Function: <code>response_status</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145ea0b)
Location: block/sed-opal.c:921
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8148a8cb)
Location: block/sed-opal.c:933
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bf505)
Location: block/sed-opal.c:950
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d3995)
Location: block/sed-opal.c:950
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815007b3)
Location: block/sed-opal.c:981
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151e70b)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 response_status(const struct parsed_resp *resp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157c7e0)
Location: block/sed-opal.c:982
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff8157c7e0-ffffffff8157c88c: response_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 response_status(const struct parsed_resp *resp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81599820)
Location: block/sed-opal.c:982
Inline: False
Direct callers:
  - block/sed-opal.c:end_session_cont
```
**Symbols:**

```
ffffffff81599820-ffffffff815998cc: response_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0c3a)
Location: block/sed-opal.c:982
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81609477)
Location: block/sed-opal.c:982
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bd397)
Location: block/sed-opal.c:982
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e011)
Location: block/sed-opal.c:1022
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bdb71)
Location: block/sed-opal.c:1030
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff818022d1)
Location: block/sed-opal.c:1147
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff80001062738c)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cf144)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c87fc)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000458db8)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81516ceb)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81506ffb)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81512d7b)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152c53b)
Location: block/sed-opal.c:980
Inline: True
Inline callers:
  - block/sed-opal.c:parse_and_check_status
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
