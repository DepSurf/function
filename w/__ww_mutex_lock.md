# Function: <code>__ww_mutex_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81822180)
Location: kernel/locking/mutex.c:914
Inline: False
```
**Symbols:**

```
ffffffff81822180-ffffffff81822220: __ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c5e0)
Location: kernel/locking/mutex.c:918
Inline: False
```
**Symbols:**

```
ffffffff8189c5e0-ffffffff8189c680: __ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __ww_mutex_lock(struct ww_mutex *lock, struct ww_acquire_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d1320)
Location: kernel/locking/mutex.c:1018
Inline: True
```
**Symbols:**

```
ffffffff818d0400-ffffffff818d044e: __ww_mutex_lock.part.3 (STB_LOCAL)
ffffffff818d1320-ffffffff818d137d: __ww_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819081a0)
Location: kernel/locking/mutex.c:897
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff819081a0-ffffffff81908848: __ww_mutex_lock.isra.3 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81992280)
Location: kernel/locking/mutex.c:897
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81992280-ffffffff819928e3: __ww_mutex_lock.isra.3 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff819ee2d0)
Location: kernel/locking/mutex.c:898
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff819ee2d0-ffffffff819ee92d: __ww_mutex_lock.isra.6 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a29540)
Location: kernel/locking/mutex.c:1076
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a29540-ffffffff81a29c8b: __ww_mutex_lock.isra.11 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a99b70)
Location: kernel/locking/mutex.c:1081
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a99b70-ffffffff81a9a35d: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81ad14c0)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81ad14c0-ffffffff81ad1cad: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81bc96c0)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81bc96c0-ffffffff81bc9e2a: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c424e0)
Location: kernel/locking/mutex.c:1110
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81c424e0-ffffffff81c42c7b: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81c34ac0)
Location: kernel/locking/mutex.c:1108
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81c34ac0-ffffffff81c352df: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81d53350)
Location: kernel/locking/mutex.c:733
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81d53350-ffffffff81d53ad8: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81f236f0)
Location: kernel/locking/mutex.c:751
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81f236f0-ffffffff81f24161: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff820cebd0)
Location: kernel/locking/mutex.c:751
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff820cebd0-ffffffff820cf637: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff821539d0)
Location: kernel/locking/mutex.c:751
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff821539d0-ffffffff821543ab: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff82236810)
Location: kernel/locking/mutex.c:756
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff82236810-ffffffff822371eb: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffff800010da37f0)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffff800010da37f0-ffff800010da4074: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (c0e9b794)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
c0e9b794-c0e9bfc4: __ww_mutex_lock.constprop.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (c000000000ee5e50)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
c000000000ee5e50-c000000000ee69cc: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffe0008c6bd8)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffe0008c6bd8-ffffffe0008c70ee: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a70330)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a70330-ffffffff81a70b1d: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81a2c720)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81a2c720-ffffffff81a2cf0d: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81adc740)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81adc740-ffffffff81adcf2d: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
In kernel/locking/mutex.c (ffffffff81ae9260)
Location: kernel/locking/mutex.c:1107
Inline: True
Direct callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
```
**Symbols:**

```
ffffffff81ae9260-ffffffff81ae9a60: __ww_mutex_lock.isra.0 (STB_LOCAL)
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
</ul>
