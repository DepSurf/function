# Function: <code>threshold_create_bank</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810485a6)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:677
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104894e)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:820
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104b32c)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1177
Inline: True
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104ac33)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1187
Inline: True
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104e61c)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1172
Inline: True
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81051264)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:1223
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e91b)
Location: arch/x86/kernel/cpu/mce/amd.c:1223
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810519eb)
Location: arch/x86/kernel/cpu/mce/amd.c:1303
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105231d)
Location: arch/x86/kernel/cpu/mce/amd.c:1305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810564e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff810564e0-ffffffff810566b9: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810553f0)
Location: arch/x86/kernel/cpu/mce/amd.c:1331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff810553f0-ffffffff810555db: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056ae0)
Location: arch/x86/kernel/cpu/mce/amd.c:1331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff81056ae0-ffffffff81056d99: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f700)
Location: arch/x86/kernel/cpu/mce/amd.c:1344
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff8105f700-ffffffff8105f9e2: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106bfd0)
Location: arch/x86/kernel/cpu/mce/amd.c:1168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff8106bfd0-ffffffff8106c28f: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107bfe0)
Location: arch/x86/kernel/cpu/mce/amd.c:1175
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff8107bfe0-ffffffff8107c2aa: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e2e0)
Location: arch/x86/kernel/cpu/mce/amd.c:1171
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff8107e2e0-ffffffff8107e5c5: threshold_create_bank (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int threshold_create_bank(struct threshold_bank **bp, unsigned int cpu, unsigned int bank);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810857c0)
Location: arch/x86/kernel/cpu/mce/amd.c:1221
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_create_device
```
**Symbols:**

```
ffffffff810857c0-ffffffff81085ad3: threshold_create_bank (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105241d)
Location: arch/x86/kernel/cpu/mce/amd.c:1305
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041e0d)
Location: arch/x86/kernel/cpu/mce/amd.c:1305
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810522cd)
Location: arch/x86/kernel/cpu/mce/amd.c:1305
Inline: True
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105370d)
Location: arch/x86/kernel/cpu/mce/amd.c:1305
Inline: True
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
