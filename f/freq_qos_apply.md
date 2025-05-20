# Function: <code>freq_qos_apply</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106d60)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffff81106d60-ffffffff81106daa: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811119f8)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff81111d10-ffffffff81111d5a: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110ead8)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8110ede0-ffffffff8110ee2a: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f578)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8110f880-ffffffff8110f8ca: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112eec8)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8112f1d0-ffffffff8112f21a: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81150428)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff811507c0-ffffffff81150830: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117ed88)
Location: kernel/power/qos.c:493
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8117f170-ffffffff8117f1e0: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f9d8)
Location: kernel/power/qos.c:498
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8118fdc0-ffffffff8118fe30: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e398)
Location: kernel/power/qos.c:503
Inline: True
Inline callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
Direct callers:
  - kernel/power/qos.c:freq_qos_update_request
  - kernel/power/qos.c:freq_qos_add_request
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8119e780-ffffffff8119e7f0: freq_qos_apply (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016da58)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffff80001016da58-ffff80001016daf0: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b89a8)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
c03b89a8-c03b8a08: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c51f0)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
c0000000001c51f0-c0000000001c5254: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010d0f0)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffe00010d0f0-ffffffe00010d162: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81100070)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffff81100070-ffffffff811000ba: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f0260)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffff810f0260-ffffffff810f02aa: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fd230)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffff810fd230-ffffffff810fd27a: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int freq_qos_apply(struct freq_qos_request *req, enum pm_qos_req_action action, s32 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811084a0)
Location: kernel/power/qos.c:718
Inline: True
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_add_request
```
**Symbols:**

```
ffffffff811084a0-ffffffff811084ea: freq_qos_apply (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
