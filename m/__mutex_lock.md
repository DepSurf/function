# Function: <code>__mutex_lock</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907b70)
Location: kernel/locking/mutex.c:890
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81907b70-ffffffff8190804b: __mutex_lock.isra.2 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81991c60)
Location: kernel/locking/mutex.c:890
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81991c60-ffffffff8199212f: __mutex_lock.isra.2 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff819eea10)
Location: kernel/locking/mutex.c:891
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff819eea10-ffffffff819eeee1: __mutex_lock.isra.5 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a29d70)
Location: kernel/locking/mutex.c:1069
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a29d70-ffffffff81a2a230: __mutex_lock.isra.10 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a9a4c0)
Location: kernel/locking/mutex.c:1074
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a9a4c0-ffffffff81a9a9aa: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1e10)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81ad1e10-ffffffff81ad22fa: __mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81bc9f90)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81bc9f90-ffffffff81bca41c: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c42de0)
Location: kernel/locking/mutex.c:1103
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81c42de0-ffffffff81c43274: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c34450)
Location: kernel/locking/mutex.c:1101
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81c34450-ffffffff81c3493a: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81d52d40)
Location: kernel/locking/mutex.c:726
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81d52d40-ffffffff81d531ca: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81f24310)
Location: kernel/locking/mutex.c:744
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81f24310-ffffffff81f24a92: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff820cf830)
Location: kernel/locking/mutex.c:744
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff820cf830-ffffffff820cffc9: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff82153050)
Location: kernel/locking/mutex.c:744
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff82153050-ffffffff8215378a: __mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff82235e90)
Location: kernel/locking/mutex.c:749
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff82235e90-ffffffff822365ca: __mutex_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da3008)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffff800010da3008-ffff800010da35f0: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (c0e9c1ac)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
c0e9c1ac-c0e9c75c: __mutex_lock.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5450)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
c000000000ee5450-c000000000ee5be0: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c7156)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffe0008c7156-ffffffe0008c7442: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a70c80)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a70c80-ffffffff81a7116a: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2d070)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a2d070-ffffffff81a2d55a: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add090)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81add090-ffffffff81add57a: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae8c20)
Location: kernel/locking/mutex.c:1100
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81ae8c20-ffffffff81ae913b: __mutex_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
