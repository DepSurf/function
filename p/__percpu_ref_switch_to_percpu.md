# Function: <code>__percpu_ref_switch_to_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __percpu_ref_switch_to_percpu(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff813fef70)
Location: lib/percpu-refcount.c:226
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff813fef70-ffffffff813ff07b: __percpu_ref_switch_to_percpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __percpu_ref_switch_to_percpu(struct percpu_ref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81446660)
Location: lib/percpu-refcount.c:226
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_switch_to_percpu
```
**Symbols:**

```
ffffffff81446660-ffffffff8144676b: __percpu_ref_switch_to_percpu (STB_LOCAL)
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
In lib/percpu-refcount.c (ffffffff814650b2)
Location: lib/percpu-refcount.c:187
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8146a0c2)
Location: lib/percpu-refcount.c:187
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff814963b4)
Location: lib/percpu-refcount.c:187
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff814cb609)
Location: lib/percpu-refcount.c:187
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff814e0339)
Location: lib/percpu-refcount.c:187
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8150c2c4)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8152a114)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8158d8c4)
Location: lib/percpu-refcount.c:195
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815aa532)
Location: lib/percpu-refcount.c:229
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815b5152)
Location: lib/percpu-refcount.c:235
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8161b4c2)
Location: lib/percpu-refcount.c:235
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff816e8cc1)
Location: lib/percpu-refcount.c:236
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff817d8d41)
Location: lib/percpu-refcount.c:237
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81817d21)
Location: lib/percpu-refcount.c:237
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8185d021)
Location: lib/percpu-refcount.c:237
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffff800010635198)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (c07db218)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (c0000000007daa04)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffe000462c48)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815226f4)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815129de)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8151e784)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81538018)
Location: lib/percpu-refcount.c:194
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
</ul>
