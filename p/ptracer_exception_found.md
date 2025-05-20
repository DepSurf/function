# Function: <code>ptracer_exception_found</code>

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
In security/yama/yama_lsm.c (ffffffff81395162)
Location: security/yama/yama_lsm.c:243
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff813d104b)
Location: security/yama/yama_lsm.c:314
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff813e874b)
Location: security/yama/yama_lsm.c:314
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff813f48f9)
Location: security/yama/yama_lsm.c:314
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
In security/yama/yama_lsm.c (ffffffff8141cd39)
Location: security/yama/yama_lsm.c:314
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
In security/yama/yama_lsm.c (ffffffff8144f060)
Location: security/yama/yama_lsm.c:309
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
In security/yama/yama_lsm.c (ffffffff8146c0ca)
Location: security/yama/yama_lsm.c:309
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
In security/yama/yama_lsm.c (ffffffff814990c9)
Location: security/yama/yama_lsm.c:305
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
In security/yama/yama_lsm.c (ffffffff814b2ff9)
Location: security/yama/yama_lsm.c:305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptracer_exception_found(struct task_struct *tracer, struct task_struct *tracee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff81511ba0)
Location: security/yama/yama_lsm.c:305
Inline: False
```
**Symbols:**

```
ffffffff81511ba0-ffffffff81511c3d: ptracer_exception_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptracer_exception_found(struct task_struct *tracer, struct task_struct *tracee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffff8152e9f0)
Location: security/yama/yama_lsm.c:305
Inline: False
```
**Symbols:**

```
ffffffff8152e9f0-ffffffff8152eab5: ptracer_exception_found (STB_LOCAL)
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
In security/yama/yama_lsm.c (ffffffff815352c6)
Location: security/yama/yama_lsm.c:305
Inline: True
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
In security/yama/yama_lsm.c (ffffffff815937e0)
Location: security/yama/yama_lsm.c:305
Inline: True
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
In security/yama/yama_lsm.c (ffffffff81635ac6)
Location: security/yama/yama_lsm.c:305
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff816ec7d6)
Location: security/yama/yama_lsm.c:306
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff81726c06)
Location: security/yama/yama_lsm.c:306
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
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
In security/yama/yama_lsm.c (ffffffff81767e56)
Location: security/yama/yama_lsm.c:306
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptrace_access_check
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffff8000105aa89c)
Location: security/yama/yama_lsm.c:305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c075a81c)
Location: security/yama/yama_lsm.c:305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (c00000000072872c)
Location: security/yama/yama_lsm.c:305
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/yama/yama_lsm.c (ffffffe0003f3742)
Location: security/yama/yama_lsm.c:305
Inline: True
```
</details>
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
In security/yama/yama_lsm.c (ffffffff814ab5d9)
Location: security/yama/yama_lsm.c:305
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
In security/yama/yama_lsm.c (ffffffff8149bff9)
Location: security/yama/yama_lsm.c:305
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
In security/yama/yama_lsm.c (ffffffff814a7679)
Location: security/yama/yama_lsm.c:305
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
In security/yama/yama_lsm.c (ffffffff814bffcb)
Location: security/yama/yama_lsm.c:305
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
</ul>
