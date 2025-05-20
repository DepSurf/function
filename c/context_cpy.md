# Function: <code>context_cpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8134e952)
Location: security/selinux/ss/context.h:117
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff81356a6a)
Location: security/selinux/ss/context.h:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81384942)
Location: security/selinux/ss/context.h:117
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff8138caee)
Location: security/selinux/ss/context.h:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8139b3d2)
Location: security/selinux/ss/context.h:117
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813a36fe)
Location: security/selinux/ss/context.h:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813b1b02)
Location: security/selinux/ss/context.h:117
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813ba163)
Location: security/selinux/ss/context.h:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff813d7c42)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff813e02c3)
Location: security/selinux/ss/context.h:118
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8140827b)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_insert
```
```
In security/selinux/ss/services.c (ffffffff814107d3)
Location: security/selinux/ss/context.h:118
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
In security/selinux/ss/sidtab.c (ffffffff8142487a)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff8145240c)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff8146c1b7)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff814c0722)
Location: security/selinux/ss/context.h:150
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff814de1a2)
Location: security/selinux/ss/context.h:150
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff814e4b15)
Location: security/selinux/ss/context.h:150
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff8153e161)
Location: security/selinux/ss/context.h:150
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff815d5b72)
Location: security/selinux/ss/context.h:150
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff81683dcc)
Location: security/selinux/ss/context.h:151
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff816bc12c)
Location: security/selinux/ss/context.h:151
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff816f8c5c)
Location: security/selinux/ss/context.h:151
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffff80001055b084)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (c070f8ac)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (c0000000006ba2b0)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffe0003b1ed2)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff81464797)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff814551c7)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff81460837)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
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
In security/selinux/ss/sidtab.c (ffffffff81478037)
Location: security/selinux/ss/context.h:118
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_set_initial
```
</details>
</li>
</ul>

## Differences
