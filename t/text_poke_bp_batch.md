# Function: <code>text_poke_bp_batch</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a350)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8103a350-ffffffff8103a4a3: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ab30)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8103ab30-ffffffff8103ac83: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103cfe0)
Location: arch/x86/kernel/alternative.c:1147
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff8103cfe0-ffffffff8103d165: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d460)
Location: arch/x86/kernel/alternative.c:1164
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff8103d460-ffffffff8103d643: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ec90)
Location: arch/x86/kernel/alternative.c:1085
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff8103ec90-ffffffff8103ee8e: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81044a00)
Location: arch/x86/kernel/alternative.c:1085
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff81044a00-ffffffff81044bfe: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104d030)
Location: arch/x86/kernel/alternative.c:1461
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff8104d030-ffffffff8104d2d5: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81059450)
Location: arch/x86/kernel/alternative.c:1941
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff81059450-ffffffff8105973d: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105a9f0)
Location: arch/x86/kernel/alternative.c:2166
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff8105a9f0-ffffffff8105ace4: text_poke_bp_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81061cb0)
Location: arch/x86/kernel/alternative.c:2256
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp
  - arch/x86/kernel/alternative.c:text_poke_finish
```
**Symbols:**

```
ffffffff81061cb0-ffffffff81061fa4: text_poke_bp_batch (STB_LOCAL)
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
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ac90)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8103ac90-ffffffff8103ade3: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8102a4a0)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8102a4a0-ffffffff8102a5f3: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103aaf0)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8103aaf0-ffffffff8103ac43: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void text_poke_bp_batch(struct text_poke_loc *tp, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103baf0)
Location: arch/x86/kernel/alternative.c:1028
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_apply
  - arch/x86/kernel/alternative.c:text_poke_bp
```
**Symbols:**

```
ffffffff8103baf0-ffffffff8103bc43: text_poke_bp_batch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
