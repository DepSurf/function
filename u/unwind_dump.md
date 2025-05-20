# Function: <code>unwind_dump</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069cc2)
Location: arch/x86/kernel/unwind_frame.c:24
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff81069b00-ffffffff81069b8e: unwind_dump.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81068c70)
Location: arch/x86/kernel/unwind_frame.c:28
Inline: False
```
**Symbols:**

```
ffffffff81068c70-ffffffff81068d9b: unwind_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d4f0)
Location: arch/x86/kernel/unwind_frame.c:30
Inline: False
```
**Symbols:**

```
ffffffff8106d4f0-ffffffff8106d620: unwind_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:30
Inline: False
```
**Symbols:**

```
ffffffff810703d0-ffffffff8107044d: unwind_dump (STB_LOCAL)
ffffffff810708ec-ffffffff810709a9: unwind_dump.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:30
Inline: False
```
**Symbols:**

```
ffffffff810763a0-ffffffff8107641f: unwind_dump (STB_LOCAL)
ffffffff810768fc-ffffffff810769b6: unwind_dump.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81079f60-ffffffff81079fdd: unwind_dump (STB_LOCAL)
ffffffff8107a49c-ffffffff8107a551: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff8107b050-ffffffff8107b0cb: unwind_dump (STB_LOCAL)
ffffffff8107b58c-ffffffff8107b63d: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81082460-ffffffff810824db: unwind_dump (STB_LOCAL)
ffffffff810829ac-ffffffff81082a5d: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81081f10-ffffffff81081f8b: unwind_dump (STB_LOCAL)
ffffffff81bd836b-ffffffff81bd841c: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81082d30-ffffffff81082dab: unwind_dump (STB_LOCAL)
ffffffff81bca1a8-ffffffff81bca259: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81091f60-ffffffff81091fe8: unwind_dump (STB_LOCAL)
ffffffff81c9f50f-ffffffff81c9f5d6: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810a31f0-ffffffff810a3289: unwind_dump (STB_LOCAL)
ffffffff81e4ecba-ffffffff81e4ed81: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810bb350-ffffffff810bb48f: unwind_dump (STB_LOCAL)
ffffffff820545be-ffffffff820545d3: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810be490-ffffffff810be5cf: unwind_dump (STB_LOCAL)
ffffffff820d2baf-ffffffff820d2bc4: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
```
**Symbols:**

```
ffffffff810c5610-ffffffff810c574f: unwind_dump (STB_LOCAL)
ffffffff821ada11-ffffffff821ada26: unwind_dump.cold (STB_LOCAL)
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
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff8107a050-ffffffff8107a0cb: unwind_dump (STB_LOCAL)
ffffffff8107a58c-ffffffff8107a63d: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff81069780-ffffffff810697fb: unwind_dump (STB_LOCAL)
ffffffff81069cbc-ffffffff81069d6d: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff8107a000-ffffffff8107a07b: unwind_dump (STB_LOCAL)
ffffffff8107a53c-ffffffff8107a5ed: unwind_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void unwind_dump(struct unwind_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:31
Inline: False
```
**Symbols:**

```
ffffffff8107c100-ffffffff8107c17b: unwind_dump (STB_LOCAL)
ffffffff8107c63c-ffffffff8107c6ed: unwind_dump.cold (STB_LOCAL)
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
