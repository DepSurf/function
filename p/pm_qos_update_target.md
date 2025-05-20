# Function: <code>pm_qos_update_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810cc230)
Location: kernel/power/qos.c:273
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810cc230-ffffffff810cc44d: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d0d30)
Location: kernel/power/qos.c:273
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810d0d30-ffffffff810d0f54: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d77a0)
Location: kernel/power/qos.c:273
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810d77a0-ffffffff810d79c4: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6800)
Location: kernel/power/qos.c:273
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810d6800-ffffffff810d6a11: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810de790)
Location: kernel/power/qos.c:273
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810de790-ffffffff810de9a4: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810e6dd0)
Location: kernel/power/qos.c:272
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810e6dd0-ffffffff810e6fe8: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f23d0)
Location: kernel/power/qos.c:261
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810f23d0-ffffffff810f25e8: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fa880)
Location: kernel/power/qos.c:262
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810fa880-ffffffff810faab7: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106720)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff81106720-ffffffff81106957: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81111480)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff81111480-ffffffff811115d0: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e600)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8110e600-ffffffff8110e739: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f0e0)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8110f0e0-ffffffff8110f219: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112e980)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8112e980-ffffffff8112eb67: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fde0)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8114fde0-ffffffff8114ffe1: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e6b0)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8117e6b0-ffffffff8117e8b1: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f310)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8118f310-ffffffff8118f50d: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119dcc0)
Location: kernel/power/qos.c:98
Inline: False
Direct callers:
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:freq_qos_remove_request
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff8119dcc0-ffffffff8119debd: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016d1a0)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffff80001016d1a0-ffff80001016d470: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8268)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
c03b8268-c03b84c4: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4880)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
c0000000001c4880-c0000000001c4b68: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010cb0e)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffe00010cb0e-ffffffe00010cce6: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ffa30)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810ffa30-ffffffff810ffc67: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810efc20)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810efc20-ffffffff810efe57: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fcbf0)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff810fcbf0-ffffffff810fce27: pm_qos_update_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pm_qos_update_target(struct pm_qos_constraints *c, struct plist_node *node, enum pm_qos_req_action action, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81107e20)
Location: kernel/power/qos.c:214
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - drivers/base/power/qos.c:apply_constraint
  - drivers/base/power/qos.c:apply_constraint
```
**Symbols:**

```
ffffffff81107e20-ffffffff81108070: pm_qos_update_target (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
