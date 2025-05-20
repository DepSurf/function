# Function: <code>klp_init_transition</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f9140)
Location: kernel/livepatch/transition.c:467
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
```
**Symbols:**

```
ffffffff810f9140-ffffffff810f92a2: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81103b30)
Location: kernel/livepatch/transition.c:490
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
```
**Symbols:**

```
ffffffff81103b30-ffffffff81103cd3: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110bfb0)
Location: kernel/livepatch/transition.c:463
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
```
**Symbols:**

```
ffffffff8110bfb0-ffffffff8110c13c: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811177a0)
Location: kernel/livepatch/transition.c:456
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_disable_patch
```
**Symbols:**

```
ffffffff811177a0-ffffffff8111792c: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81121bd0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81121bd0-ffffffff81121d70: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8112e1f0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8112e1f0-ffffffff8112e390: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113cae0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8113cae0-ffffffff8113cc80: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811371f0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811371f0-ffffffff81137390: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81137fa0)
Location: kernel/livepatch/transition.c:503
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81137fa0-ffffffff81138140: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8115ad10)
Location: kernel/livepatch/transition.c:503
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff8115ad10-ffffffff8115aeb0: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81184600)
Location: kernel/livepatch/transition.c:503
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81184600-ffffffff811847b4: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811bfa10)
Location: kernel/livepatch/transition.c:503
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811bfa10-ffffffff811bfbc7: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811d24f0)
Location: kernel/livepatch/transition.c:573
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811d24f0-ffffffff811d26a7: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811e7170)
Location: kernel/livepatch/transition.c:573
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811e7170-ffffffff811e7327: klp_init_transition (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3560)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
c0000000001f3560-c0000000001f37cc: klp_init_transition (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811267d0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811267d0-ffffffff81126970: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81119230)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81119230-ffffffff811193d0: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811246c0)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff811246c0-ffffffff81124860: klp_init_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_init_transition(struct klp_patch *patch, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81130d10)
Location: kernel/livepatch/transition.c:504
Inline: False
Direct callers:
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff81130d10-ffffffff81130eaf: klp_init_transition (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
