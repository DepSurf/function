# Function: <code>rfkill_set_hw_state_reason</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ba7800)
Location: net/rfkill/core.c:527
Inline: False
```
**Symbols:**

```
ffffffff81ba7800-ffffffff81ba790e: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b96990)
Location: net/rfkill/core.c:528
Inline: False
```
**Symbols:**

```
ffffffff81b96990-ffffffff81b96a9c: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:528
Inline: False
```
**Symbols:**

```
ffffffff81d41d3a-ffffffff81d41d4f: rfkill_set_hw_state_reason.cold (STB_LOCAL)
ffffffff81c63950-ffffffff81c63a54: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:528
Inline: False
```
**Symbols:**

```
ffffffff81f0e66f-ffffffff81f0e684: rfkill_set_hw_state_reason.cold (STB_LOCAL)
ffffffff81e06380-ffffffff81e06488: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:528
Inline: False
```
**Symbols:**

```
ffffffff820b562c-ffffffff820b5641: rfkill_set_hw_state_reason.cold (STB_LOCAL)
ffffffff81fdb6b0-ffffffff81fdb7b8: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:528
Inline: False
```
**Symbols:**

```
ffffffff82136bb5-ffffffff82136bca: rfkill_set_hw_state_reason.cold (STB_LOCAL)
ffffffff82057390-ffffffff8205749b: rfkill_set_hw_state_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rfkill_set_hw_state_reason(struct rfkill *rfkill, bool blocked, long unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:540
Inline: False
```
**Symbols:**

```
ffffffff822189ed-ffffffff82218a02: rfkill_set_hw_state_reason.cold (STB_LOCAL)
ffffffff82129e90-ffffffff82129f9b: rfkill_set_hw_state_reason (STB_GLOBAL)
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
