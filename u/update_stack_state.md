# Function: <code>update_stack_state</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, void *addr, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069a60)
Location: arch/x86/kernel/unwind_frame.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff81069a60-ffffffff81069afe: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81068da0)
Location: arch/x86/kernel/unwind_frame.c:196
Inline: False
```
**Symbols:**

```
ffffffff81068da0-ffffffff81068ef7: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d620)
Location: arch/x86/kernel/unwind_frame.c:206
Inline: False
```
**Symbols:**

```
ffffffff8106d620-ffffffff8106d780: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81070450)
Location: arch/x86/kernel/unwind_frame.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81070450-ffffffff810705c6: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81076420)
Location: arch/x86/kernel/unwind_frame.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81076420-ffffffff8107659c: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81079fe0)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81079fe0-ffffffff8107a14e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b0d0)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107b0d0-ffffffff8107b23e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810824e0)
Location: arch/x86/kernel/unwind_frame.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff810824e0-ffffffff8108264e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81081f90)
Location: arch/x86/kernel/unwind_frame.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81081f90-ffffffff810820fe: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082db0)
Location: arch/x86/kernel/unwind_frame.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81082db0-ffffffff81082f1e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81091df0)
Location: arch/x86/kernel/unwind_frame.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81091df0-ffffffff81091f5e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810a3050)
Location: arch/x86/kernel/unwind_frame.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810a3050-ffffffff810a31e9: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb4a0)
Location: arch/x86/kernel/unwind_frame.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810bb4a0-ffffffff810bb639: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810be5e0)
Location: arch/x86/kernel/unwind_frame.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810be5e0-ffffffff810be779: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5760)
Location: arch/x86/kernel/unwind_frame.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810c5760-ffffffff810c58f9: update_stack_state (STB_LOCAL)
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
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a0d0)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107a0d0-ffffffff8107a23e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069800)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81069800-ffffffff8106996e: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a080)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107a080-ffffffff8107a1ee: update_stack_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool update_stack_state(struct unwind_state *state, long unsigned int *next_bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c180)
Location: arch/x86/kernel/unwind_frame.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107c180-ffffffff8107c2ee: update_stack_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *next_bp</code>
</li>
<li>
<b>Param removed. </b>
<code>void *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t len</code>
</li>
</ul>
</details>
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
