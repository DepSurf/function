# Function: <code>nvm_find_target_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nvm_tgt_type *nvm_find_target_type(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81542ac0)
Location: drivers/lightnvm/core.c:38
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_target
```
**Symbols:**

```
ffffffff81542ac0-ffffffff81542b15: nvm_find_target_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nvm_tgt_type *nvm_find_target_type(const char *name, int lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815944a0)
Location: drivers/lightnvm/core.c:36
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
```
**Symbols:**

```
ffffffff815944a0-ffffffff8159453f: nvm_find_target_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nvm_tgt_type *nvm_find_target_type(const char *name, int lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c1de0)
Location: drivers/lightnvm/core.c:36
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
```
**Symbols:**

```
ffffffff815c1de0-ffffffff815c1e7f: nvm_find_target_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nvm_tgt_type *nvm_find_target_type(const char *name, int lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d7aa0)
Location: drivers/lightnvm/core.c:535
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
```
**Symbols:**

```
ffffffff815d7aa0-ffffffff815d7b3f: nvm_find_target_type (STB_GLOBAL)
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
In drivers/lightnvm/core.c (ffffffff8163f1bf)
Location: drivers/lightnvm/core.c:229
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register_tgt_type
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
In drivers/lightnvm/core.c (ffffffff8167a9a6)
Location: drivers/lightnvm/core.c:264
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
In drivers/lightnvm/core.c (ffffffff8169a2d6)
Location: drivers/lightnvm/core.c:264
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
In drivers/lightnvm/core.c (ffffffff816d2d7a)
Location: drivers/lightnvm/core.c:252
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff816f6c5a)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817afe7a)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817c49fa)
Location: drivers/lightnvm/core.c:250
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817a785a)
Location: drivers/lightnvm/core.c:250
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/lightnvm/core.c (ffff8000108e0ac0)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (c09cf67c)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (c000000000974674)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffe0005763d2)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff816bc44a)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816ea91a)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff8170515a)
Location: drivers/lightnvm/core.c:254
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
<code>int lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
