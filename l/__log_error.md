# Function: <code>__log_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __log_error(unsigned int bank, bool threshold_err, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047cd0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:312
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81047cd0-ffffffff81047dc8: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __log_error(unsigned int bank, bool deferred_err, bool threshold_err, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81047d80)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81047d80-ffffffff81047eb4: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __log_error(unsigned int bank, bool deferred_err, bool threshold_err, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff810499d0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:758
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_threshold_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff810499d0-ffffffff81049b84: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049370)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:744
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81049370-ffffffff81049472: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104cdb0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff8104cdb0-ffffffff8104ceb2: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104fa50)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:793
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff8104fa50-ffffffff8104fb50: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104d2c0)
Location: arch/x86/kernel/cpu/mce/amd.c:793
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff8104d2c0-ffffffff8104d3c0: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050200)
Location: arch/x86/kernel/cpu/mce/amd.c:873
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81050200-ffffffff81050302: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050b70)
Location: arch/x86/kernel/cpu/mce/amd.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81050b70-ffffffff81050c72: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055f60)
Location: arch/x86/kernel/cpu/mce/amd.c:889
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
```
**Symbols:**

```
ffffffff81055f60-ffffffff8105606a: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81054e60)
Location: arch/x86/kernel/cpu/mce/amd.c:889
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:log_error_deferred
```
**Symbols:**

```
ffffffff81054e60-ffffffff81054f6a: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810563f0)
Location: arch/x86/kernel/cpu/mce/amd.c:889
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff810563f0-ffffffff810564fa: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f000)
Location: arch/x86/kernel/cpu/mce/amd.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff8105f000-ffffffff8105f10a: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b7f0)
Location: arch/x86/kernel/cpu/mce/amd.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff8106b7f0-ffffffff8106b923: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107b7e0)
Location: arch/x86/kernel/cpu/mce/amd.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
**Symbols:**

```
ffffffff8107b7e0-ffffffff8107b913: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107da90)
Location: arch/x86/kernel/cpu/mce/amd.c:729
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
**Symbols:**

```
ffffffff8107da90-ffffffff8107dc12: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81084f40)
Location: arch/x86/kernel/cpu/mce/amd.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
**Symbols:**

```
ffffffff81084f40-ffffffff810850c2: __log_error (STB_LOCAL)
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
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050c70)
Location: arch/x86/kernel/cpu/mce/amd.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81050c70-ffffffff81050d72: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81040ed0)
Location: arch/x86/kernel/cpu/mce/amd.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81040ed0-ffffffff8104100c: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81050b20)
Location: arch/x86/kernel/cpu/mce/amd.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81050b20-ffffffff81050c22: __log_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __log_error(unsigned int bank, u64 status, u64 addr, u64 misc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051f60)
Location: arch/x86/kernel/cpu/mce/amd.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt
```
**Symbols:**

```
ffffffff81051f60-ffffffff81052062: __log_error (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool deferred_err</code>
</li>
<li>
<b>Param reordered. </b>
<code>bank, threshold_err, misc</code> ➡️ <code>bank, deferred_err, threshold_err, misc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 status</code>
</li>
<li>
<b>Param added. </b>
<code>u64 addr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool deferred_err</code>
</li>
<li>
<b>Param removed. </b>
<code>bool threshold_err</code>
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
