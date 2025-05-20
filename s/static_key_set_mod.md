# Function: <code>static_key_set_mod</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff811b4833)
Location: kernel/jump_label.c:396
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811c7f50)
Location: kernel/jump_label.c:450
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
**Symbols:**

```
ffffffff811c7f50-ffffffff811c7f7c: static_key_set_mod.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811e84a0)
Location: kernel/jump_label.c:468
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
**Symbols:**

```
ffffffff811e84a0-ffffffff811e84cc: static_key_set_mod.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9160)
Location: kernel/jump_label.c:472
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
**Symbols:**

```
ffffffff811f9160-ffffffff811f918c: static_key_set_mod.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff81211090)
Location: kernel/jump_label.c:526
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
**Symbols:**

```
ffffffff81211090-ffffffff812110be: static_key_set_mod.isra.0 (STB_LOCAL)
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
In kernel/jump_label.c (ffffffff8121eb80)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/jump_label.c (ffffffff8124b291)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff812556f1)
Location: kernel/jump_label.c:536
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff81259bf1)
Location: kernel/jump_label.c:538
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff81295961)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff812eac68)
Location: kernel/jump_label.c:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff81354bd8)
Location: kernel/jump_label.c:563
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff8138602f)
Location: kernel/jump_label.c:563
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffffffff813af4ef)
Location: kernel/jump_label.c:563
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
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
In kernel/jump_label.c (ffff8000102aad14)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f364)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812171d0)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/jump_label.c (ffffffff81209f30)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/jump_label.c (ffffffff81214f70)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/jump_label.c (ffffffff81223f20)
Location: kernel/jump_label.c:528
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
</ul>

## Differences
