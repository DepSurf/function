# Function: <code>intel_gtt_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81522400)
Location: drivers/char/agp/intel-gtt.c:607
Inline: False
```
**Symbols:**

```
ffffffff81522400-ffffffff81522c41: intel_gtt_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff815752a0)
Location: drivers/char/agp/intel-gtt.c:609
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff815752a0-ffffffff81575b30: intel_gtt_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff815a1930)
Location: drivers/char/agp/intel-gtt.c:609
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff815a1930-ffffffff815a21bd: intel_gtt_init (STB_LOCAL)
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
In drivers/char/agp/intel-gtt.c (ffffffff815b5456)
Location: drivers/char/agp/intel-gtt.c:602
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
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
In drivers/char/agp/intel-gtt.c (ffffffff8161c466)
Location: drivers/char/agp/intel-gtt.c:602
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
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
In drivers/char/agp/intel-gtt.c (ffffffff8165619b)
Location: drivers/char/agp/intel-gtt.c:602
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
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
In drivers/char/agp/intel-gtt.c (ffffffff81673fa1)
Location: drivers/char/agp/intel-gtt.c:602
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff816a9ba0-ffffffff816a9e8a: intel_gtt_init (STB_LOCAL)
ffffffff816aa0f2-ffffffff816aa5d1: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff816cc8e0-ffffffff816ccbca: intel_gtt_init (STB_LOCAL)
ffffffff816cce32-ffffffff816cd312: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:604
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81781930-ffffffff817819d4: intel_gtt_init (STB_LOCAL)
ffffffff8178205f-ffffffff817821d1: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:604
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff817996a0-ffffffff81799744: intel_gtt_init (STB_LOCAL)
ffffffff81c09fb8-ffffffff81c0a12a: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:604
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff8177b810-ffffffff8177ba55: intel_gtt_init (STB_LOCAL)
ffffffff81bfb97e-ffffffff81bfbb90: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:604
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff818018b0-ffffffff81801aef: intel_gtt_init (STB_LOCAL)
ffffffff81cfc579-ffffffff81cfc78a: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:605
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81940f80-ffffffff819411f2: intel_gtt_init (STB_LOCAL)
ffffffff81ec4db4-ffffffff81ec4fa8: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81aa3a20)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81aa3a20-ffffffff81aa3fa1: intel_gtt_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81aef300)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81aef300-ffffffff81aef882: intel_gtt_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/intel-gtt.c (ffffffff81b42840)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81b42840-ffffffff81b42dc7: intel_gtt_init (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff81692330-ffffffff8169261a: intel_gtt_init (STB_LOCAL)
ffffffff81692882-ffffffff81692d61: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff8166fd20-ffffffff8167000a: intel_gtt_init (STB_LOCAL)
ffffffff81670272-ffffffff81670752: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff816c05a0-ffffffff816c088a: intel_gtt_init (STB_LOCAL)
ffffffff816c0af2-ffffffff816c0fd2: intel_gtt_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int intel_gtt_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/intel-gtt.c (0)
Location: drivers/char/agp/intel-gtt.c:602
Inline: False
Direct callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
**Symbols:**

```
ffffffff816dab70-ffffffff816dae5a: intel_gtt_init (STB_LOCAL)
ffffffff816db0c2-ffffffff816db5a2: intel_gtt_init.cold (STB_LOCAL)
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
