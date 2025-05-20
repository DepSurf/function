# Function: <code>elants_i2c_mt_event</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817014d1)
Location: drivers/input/touchscreen/elants_i2c.c:784
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716d11)
Location: drivers/input/touchscreen/elants_i2c.c:784
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787ee1)
Location: drivers/input/touchscreen/elants_i2c.c:785
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8f7a)
Location: drivers/input/touchscreen/elants_i2c.c:784
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f061a)
Location: drivers/input/touchscreen/elants_i2c.c:785
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183097a)
Location: drivers/input/touchscreen/elants_i2c.c:780
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff818622aa)
Location: drivers/input/touchscreen/elants_i2c.c:780
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81934c20)
Location: drivers/input/touchscreen/elants_i2c.c:848
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81934c20-ffffffff81934e36: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193bc90)
Location: drivers/input/touchscreen/elants_i2c.c:856
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8193bc90-ffffffff8193bea6: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191f170)
Location: drivers/input/touchscreen/elants_i2c.c:926
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8191f170-ffffffff8191f3dc: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c1f20)
Location: drivers/input/touchscreen/elants_i2c.c:970
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff819c1f20-ffffffff819c2186: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b222e0)
Location: drivers/input/touchscreen/elants_i2c.c:970
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81b222e0-ffffffff81b2253e: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb4800)
Location: drivers/input/touchscreen/elants_i2c.c:970
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81cb4800-ffffffff81cb4a5e: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1be40)
Location: drivers/input/touchscreen/elants_i2c.c:970
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81d1be40-ffffffff81d1c0b2: elants_i2c_mt_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elants_i2c_mt_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd1b90)
Location: drivers/input/touchscreen/elants_i2c.c:970
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81dd1b90-ffffffff81dd1e02: elants_i2c_mt_event (STB_LOCAL)
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185643a)
Location: drivers/input/touchscreen/elants_i2c.c:780
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187156a)
Location: drivers/input/touchscreen/elants_i2c.c:780
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t packet_size</code>
</li>
</ul>
</details>
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
