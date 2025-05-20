# Function: <code>acpi_idle_do_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814acc88)
Location: drivers/acpi/processor_idle.c:683
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
**Symbols:**

```
ffffffff814acc88-ffffffff814accb8: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fc523)
Location: drivers/acpi/processor_idle.c:648
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff814fc523-ffffffff814fc553: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff818d3ff5)
Location: drivers/acpi/processor_idle.c:649
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff818d3ff5-ffffffff818d4025: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8190b170)
Location: drivers/acpi/processor_idle.c:649
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_freeze
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff8190b170-ffffffff8190b1b1: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81995510)
Location: drivers/acpi/processor_idle.c:651
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81995510-ffffffff81995541: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819f1a50)
Location: drivers/acpi/processor_idle.c:655
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff819f1a50-ffffffff819f1a81: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a2cf60)
Location: drivers/acpi/processor_idle.c:656
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81a2cf60-ffffffff81a2cf91: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a9d0d0)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81a9d0d0-ffffffff81a9d101: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81ad4920)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81ad4920-ffffffff81ad4951: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e2057)
Location: drivers/acpi/processor_idle.c:519
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81c45420)
Location: drivers/acpi/processor_idle.c:511
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81c45420-ffffffff81c45478: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81c386a0)
Location: drivers/acpi/processor_idle.c:547
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81c386a0-ffffffff81c386f8: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81d56f80)
Location: drivers/acpi/processor_idle.c:547
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81d56f80-ffffffff81d56fd8: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81f29460)
Location: drivers/acpi/processor_idle.c:546
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81f29460-ffffffff81f29511: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff820d5280)
Location: drivers/acpi/processor_idle.c:562
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff820d5280-ffffffff820d533a: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff821439c0)
Location: drivers/acpi/processor_idle.c:565
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff821439c0-ffffffff82143a32: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff822260e0)
Location: drivers/acpi/processor_idle.c:565
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff822260e0-ffffffff82226152: acpi_idle_do_entry (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a73790)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81a73790-ffffffff81a737c1: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a2fb00)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81a2fb00-ffffffff81a2fb4a: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81adfba0)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81adfba0-ffffffff81adfbd1: acpi_idle_do_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_idle_do_entry(struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81aec3a0)
Location: drivers/acpi/processor_idle.c:651
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
**Symbols:**

```
ffffffff81aec3a0-ffffffff81aec3d1: acpi_idle_do_entry (STB_LOCAL)
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
