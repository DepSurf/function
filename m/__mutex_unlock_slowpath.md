# Function: <code>__mutex_unlock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mutex_unlock_slowpath(atomic_t *lock_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81822380)
Location: kernel/locking/mutex.c:757
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81822380-ffffffff818223c5: __mutex_unlock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mutex_unlock_slowpath(atomic_t *lock_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c7e0)
Location: kernel/locking/mutex.c:761
Inline: False
Direct callers:
  - kernel/locking/mutex.c:ww_mutex_unlock
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff8189c7e0-ffffffff8189c874: __mutex_unlock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d0450)
Location: kernel/locking/mutex.c:848
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff818d0450-ffffffff818d0565: __mutex_unlock_slowpath.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907990)
Location: kernel/locking/mutex.c:1012
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81907990-ffffffff81907aad: __mutex_unlock_slowpath.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991a80)
Location: kernel/locking/mutex.c:1012
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81991a80-ffffffff81991b9d: __mutex_unlock_slowpath.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee0f0)
Location: kernel/locking/mutex.c:1013
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff819ee0f0-ffffffff819ee20f: __mutex_unlock_slowpath.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29360)
Location: kernel/locking/mutex.c:1191
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81a29360-ffffffff81a2947f: __mutex_unlock_slowpath.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a999f0)
Location: kernel/locking/mutex.c:1196
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81a999f0-ffffffff81a99b0f: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1340)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81ad1340-ffffffff81ad145f: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81bc9520)
Location: kernel/locking/mutex.c:1222
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81bc9520-ffffffff81bc963f: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c42340)
Location: kernel/locking/mutex.c:1225
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81c42340-ffffffff81c4245f: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c342b0)
Location: kernel/locking/mutex.c:1223
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81c342b0-ffffffff81c343cf: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81d52ba0)
Location: kernel/locking/mutex.c:845
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81d52ba0-ffffffff81d52cb1: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81f234b0)
Location: kernel/locking/mutex.c:901
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff81f234b0-ffffffff81f235cf: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff820ce950)
Location: kernel/locking/mutex.c:901
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff820ce950-ffffffff820cea6f: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff82152dc0)
Location: kernel/locking/mutex.c:901
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff82152dc0-ffffffff82152f07: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff82235c00)
Location: kernel/locking/mutex.c:906
Inline: True
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:ww_mutex_unlock
```
**Symbols:**

```
ffffffff82235c00-ffffffff82235d47: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da2dc0)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffff800010da2dc0-ffff800010da2f54: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (c0e9b460)
Location: kernel/locking/mutex.c:1222
Inline: True
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
c0e9b460-c0e9b5d4: __mutex_unlock_slowpath.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5050)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
c000000000ee5050-c000000000ee5228: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c6a32)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffe0008c6a32-ffffffe0008c6b5c: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a701b0)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81a701b0-ffffffff81a702cf: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2c5a0)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81a2c5a0-ffffffff81a2c6bf: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81adc5c0)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81adc5c0-ffffffff81adc6df: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae89b0)
Location: kernel/locking/mutex.c:1222
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_unlock
```
**Symbols:**

```
ffffffff81ae89b0-ffffffff81ae8acd: __mutex_unlock_slowpath.isra.0 (STB_LOCAL)
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
