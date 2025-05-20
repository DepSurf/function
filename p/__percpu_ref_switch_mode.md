# Function: <code>__percpu_ref_switch_mode</code>

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
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81464fb0)
Location: lib/percpu-refcount.c:212
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff81464fb0-ffffffff8146512b: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81469fc0)
Location: lib/percpu-refcount.c:212
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff81469fc0-ffffffff8146a13a: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814962b0)
Location: lib/percpu-refcount.c:212
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff814962b0-ffffffff81496427: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814cb510)
Location: lib/percpu-refcount.c:212
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff814cb510-ffffffff814cb68f: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e0240)
Location: lib/percpu-refcount.c:212
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff814e0240-ffffffff814e03bf: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150c1c0)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff8150c1c0-ffffffff8150c354: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8152a010)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff8152a010-ffffffff8152a1a4: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158d7c0)
Location: lib/percpu-refcount.c:223
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff8158d7c0-ffffffff8158d954: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa420)
Location: lib/percpu-refcount.c:257
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff815aa420-ffffffff815aa5ce: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b5040)
Location: lib/percpu-refcount.c:263
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff815b5040-ffffffff815b51ee: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b3b0)
Location: lib/percpu-refcount.c:263
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff8161b3b0-ffffffff8161b581: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e8b80)
Location: lib/percpu-refcount.c:264
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff816e8b80-ffffffff816e8d8c: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d8c00)
Location: lib/percpu-refcount.c:265
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff817d8c00-ffffffff817d8e17: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81817be0)
Location: lib/percpu-refcount.c:265
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff81817be0-ffffffff81817df7: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185cee0)
Location: lib/percpu-refcount.c:265
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff8185cee0-ffffffff8185d0f7: __percpu_ref_switch_mode (STB_LOCAL)
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
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff800010635020)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffff800010635020-ffff800010635258: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07db0d4)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
c07db0d4-c07db304: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007da850)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
c0000000007da850-c0000000007dab5c: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe000462b1a)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffe000462b1a-ffffffe000462ce8: __percpu_ref_switch_mode (STB_LOCAL)
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
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815225f0)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff815225f0-ffffffff81522784: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815128e0)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff815128e0-ffffffff81512a6e: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e680)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff8151e680-ffffffff8151e814: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __percpu_ref_switch_mode(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81537f10)
Location: lib/percpu-refcount.c:222
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff81537f10-ffffffff815380b9: __percpu_ref_switch_mode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
