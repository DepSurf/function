# Function: <code>field_has_hist_vars</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c0b0)
Location: kernel/trace/trace_events_hist.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff8119c0b0-ffffffff8119c110: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa3b0)
Location: kernel/trace/trace_events_hist.c:1461
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff811aa3b0-ffffffff811aa3fc: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf85c)
Location: kernel/trace/trace_events_hist.c:1615
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811b9a70-ffffffff811b9ad3: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cb0ac)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811c5040-ffffffff811c50a3: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e6fb8)
Location: kernel/trace/trace_events_hist.c:780
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
```
**Symbols:**

```
ffffffff811e1ef0-ffffffff811e1f3d: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e4978)
Location: kernel/trace/trace_events_hist.c:783
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
```
**Symbols:**

```
ffffffff811dfb10-ffffffff811dfb5d: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e5f58)
Location: kernel/trace/trace_events_hist.c:799
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_field
  - kernel/trace/trace_events_hist.c:create_key_field
```
**Symbols:**

```
ffffffff811e0c20-ffffffff811e0c6d: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81216d9e)
Location: kernel/trace/trace_events_hist.c:823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
```
**Symbols:**

```
ffffffff81210930-ffffffff81210980: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812550b1)
Location: kernel/trace/trace_events_hist.c:997
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff8124b390-ffffffff8124b3f8: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a4547)
Location: kernel/trace/trace_events_hist.c:1030
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff81299ba0-ffffffff81299c08: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812c241a)
Location: kernel/trace/trace_events_hist.c:1027
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff812b7050-ffffffff812b70b8: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool field_has_hist_vars(struct hist_field *hist_field, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dec18)
Location: kernel/trace/trace_events_hist.c:1020
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
  - kernel/trace/trace_events_hist.c:create_key_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
  - kernel/trace/trace_events_hist.c:field_has_hist_vars
```
**Symbols:**

```
ffffffff812d36a0-ffffffff812d3708: field_has_hist_vars (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024a464)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffff800010244e20-ffff800010244eb4: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e54b8)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
c0000000002d8c70-c0000000002d8d18: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c36cc)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811bd660-ffffffff811bd6c3: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b64ac)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811b0440-ffffffff811b04a3: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c149c)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811bb430-ffffffff811bb493: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cf53c)
Location: kernel/trace/trace_events_hist.c:1689
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
**Symbols:**

```
ffffffff811c94d0-ffffffff811c9533: field_has_hist_vars.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
