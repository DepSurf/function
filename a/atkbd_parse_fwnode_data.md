# Function: <code>atkbd_parse_fwnode_data</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void atkbd_parse_fwnode_data(struct serio *serio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81931db0)
Location: drivers/input/keyboard/atkbd.c:1201
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81931db0-ffffffff81931e37: atkbd_parse_fwnode_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void atkbd_parse_fwnode_data(struct serio *serio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81939010)
Location: drivers/input/keyboard/atkbd.c:1201
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81939010-ffffffff81939097: atkbd_parse_fwnode_data (STB_LOCAL)
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
In drivers/input/keyboard/atkbd.c (ffffffff8191d6ed)
Location: drivers/input/keyboard/atkbd.c:1201
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In drivers/input/keyboard/atkbd.c (ffffffff819c02d5)
Location: drivers/input/keyboard/atkbd.c:1201
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In drivers/input/keyboard/atkbd.c (ffffffff81b21022)
Location: drivers/input/keyboard/atkbd.c:1189
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In drivers/input/keyboard/atkbd.c (ffffffff81cb32c2)
Location: drivers/input/keyboard/atkbd.c:1189
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In drivers/input/keyboard/atkbd.c (ffffffff81d1a8ef)
Location: drivers/input/keyboard/atkbd.c:1208
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In drivers/input/keyboard/atkbd.c (ffffffff81dd071c)
Location: drivers/input/keyboard/atkbd.c:1252
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
