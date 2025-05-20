# Function: <code>create_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141e0b0)
Location: drivers/pinctrl/core.c:690
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff8141e0b0-ffffffff8141e121: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814667e0)
Location: drivers/pinctrl/core.c:703
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff814667e0-ffffffff81466851: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81485ad0)
Location: drivers/pinctrl/core.c:703
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff81485ad0-ffffffff81485b41: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148f270)
Location: drivers/pinctrl/core.c:892
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8148f270-ffffffff8148f2d4: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cb3d0)
Location: drivers/pinctrl/core.c:892
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff814cb3d0-ffffffff814cb434: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fc360)
Location: drivers/pinctrl/core.c:892
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff814fc360-ffffffff814fc3c4: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81510030)
Location: drivers/pinctrl/core.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff81510030-ffffffff81510094: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153e720)
Location: drivers/pinctrl/core.c:896
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8153e720-ffffffff8153e781: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8155f5c0)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8155f5c0-ffffffff8155f621: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160332a)
Location: drivers/pinctrl/core.c:925
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8162823a)
Location: drivers/pinctrl/core.c:926
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
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
In drivers/pinctrl/core.c (ffffffff8160bd1a)
Location: drivers/pinctrl/core.c:926
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
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
In drivers/pinctrl/core.c (ffffffff8167aa2a)
Location: drivers/pinctrl/core.c:926
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
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
In drivers/pinctrl/core.c (ffffffff817960cd)
Location: drivers/pinctrl/core.c:926
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
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
In drivers/pinctrl/core.c (ffffffff818ab7dc)
Location: drivers/pinctrl/core.c:927
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
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
In drivers/pinctrl/core.c (ffffffff818ee71c)
Location: drivers/pinctrl/core.c:931
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:add_setting
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81934840)
Location: drivers/pinctrl/core.c:945
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:add_setting
```
**Symbols:**

```
ffffffff81934840-ffffffff819348dc: create_state (STB_LOCAL)
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
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068bad0)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffff80001068bad0-ffff80001068bb3c: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082ddd8)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
c082ddd8-c082de3c: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000826030)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
c000000000826030-c0000000008260dc: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000497fa6)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffe000497fa6-ffffffe000498006: create_state (STB_LOCAL)
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
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81557bb0)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff81557bb0-ffffffff81557c11: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81548070)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff81548070-ffffffff815480d1: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815538f0)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff815538f0-ffffffff81553951: create_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pinctrl_state *create_state(struct pinctrl *p, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156d780)
Location: drivers/pinctrl/core.c:924
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
**Symbols:**

```
ffffffff8156d780-ffffffff8156d7e1: create_state (STB_LOCAL)
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
