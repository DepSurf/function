# Function: <code>__do_sys_delete_module</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811310c7)
Location: kernel/module.c:961
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff8113c977)
Location: kernel/module.c:962
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff81148068)
Location: kernel/module.c:958
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff81153ea8)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81165900)
Location: kernel/module.c:973
Inline: True
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81165900-ffffffff81165b9a: __do_sys_delete_module.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1006
Inline: True
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81162050-ffffffff811622a9: __do_sys_delete_module.constprop.0 (STB_LOCAL)
ffffffff81be41f4-ffffffff81be420c: __do_sys_delete_module.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:911
Inline: True
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81162ae0-ffffffff81162d6c: __do_sys_delete_module.constprop.0 (STB_LOCAL)
ffffffff81bd6099-ffffffff81bd60b1: __do_sys_delete_module.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:912
Inline: True
Direct callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81188060-ffffffff811882e9: __do_sys_delete_module.constprop.0 (STB_LOCAL)
ffffffff81cb2836-ffffffff81cb284e: __do_sys_delete_module.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:692
Inline: True
Direct callers:
  - kernel/module/main.c:__ia32_sys_delete_module
  - kernel/module/main.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8118e140-ffffffff8118e3b9: __do_sys_delete_module.constprop.0 (STB_LOCAL)
ffffffff81e6185b-ffffffff81e61873: __do_sys_delete_module.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (ffffffff811cd190)
Location: kernel/module/main.c:693
Inline: True
Direct callers:
  - kernel/module/main.c:__ia32_sys_delete_module
  - kernel/module/main.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff811cd190-ffffffff811cd483: __do_sys_delete_module.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (ffffffff811e0a70)
Location: kernel/module/main.c:698
Inline: True
Direct callers:
  - kernel/module/main.c:__ia32_sys_delete_module
  - kernel/module/main.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff811e0a70-ffffffff811e0d63: __do_sys_delete_module.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (ffffffff811f67a0)
Location: kernel/module/main.c:698
Inline: True
Direct callers:
  - kernel/module/main.c:__ia32_sys_delete_module
  - kernel/module/main.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff811f67a0-ffffffff811f6a93: __do_sys_delete_module.isra.0 (STB_LOCAL)
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
In kernel/module.c (ffff8000101c3334)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__arm64_sys_delete_module
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
In kernel/module.c (c040a528)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_delete_module
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
In kernel/module.c (c00000000022991c)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_delete_module
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
In kernel/module.c (ffffffe0001442d2)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__se_sys_delete_module
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
In kernel/module.c (ffffffff8114c4c8)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff8113f778)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff8114a378)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
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
In kernel/module.c (ffffffff81157068)
Location: kernel/module.c:970
Inline: True
Inline callers:
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
</details>
</li>
</ul>

## Differences
