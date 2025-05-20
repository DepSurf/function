# Function: <code>__neigh_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81726db0)
Location: net/core/neighbour.c:2834
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_cleanup_and_release
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_update
```
**Symbols:**

```
ffffffff81726db0-ffffffff81726e7c: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817908d0)
Location: net/core/neighbour.c:2836
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff817908d0-ffffffff8179099c: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817be180)
Location: net/core/neighbour.c:2833
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff817be180-ffffffff817be24c: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dcbf0)
Location: net/core/neighbour.c:2883
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff817dcbf0-ffffffff817dccbe: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818577c0)
Location: net/core/neighbour.c:2883
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff818577c0-ffffffff8185788e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a2940)
Location: net/core/neighbour.c:2886
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff818a2940-ffffffff818a2a0e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c5b50)
Location: net/core/neighbour.c:3312
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff818c5b50-ffffffff818c5c1e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:3347
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81911ba0-ffffffff81911c6d: __neigh_notify (STB_LOCAL)
ffffffff819158b0-ffffffff819158c3: __neigh_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81944210)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81944210-ffffffff819442dd: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a14280)
Location: net/core/neighbour.c:3349
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81a14280-ffffffff81a1434d: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81a14590)
Location: net/core/neighbour.c:3351
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81a14590-ffffffff81a1465d: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff819faf20)
Location: net/core/neighbour.c:3355
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff819faf20-ffffffff819fafed: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81aacb60)
Location: net/core/neighbour.c:3363
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81aacb60-ffffffff81aacc2d: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c25b50)
Location: net/core/neighbour.c:3467
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81c25b50-ffffffff81c25c4e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd7da0)
Location: net/core/neighbour.c:3516
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81dd7da0-ffffffff81dd7e9e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e48b10)
Location: net/core/neighbour.c:3495
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81e48b10-ffffffff81e48c0e: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f076d0)
Location: net/core/neighbour.c:3507
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81f076d0-ffffffff81f077ce: __neigh_notify (STB_LOCAL)
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
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be40d8)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffff800010be40d8-ffff800010be41bc: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cfe588)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
c0cfe588-c0cfe668: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc7570)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
c000000000cc7570-c000000000cc76b8: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076aa40)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffe00076aa40-ffffffe00076aafa: __neigh_notify (STB_LOCAL)
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
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e41e0)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff818e41e0-ffffffff818e42ad: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189e020)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff8189e020-ffffffff8189e0ed: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81935210)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81935210-ffffffff819352dd: __neigh_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __neigh_notify(struct neighbour *n, int type, int flags, u32 pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81956920)
Location: net/core/neighbour.c:3344
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_app_ns
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_cleanup_and_release
```
**Symbols:**

```
ffffffff81956920-ffffffff819569ed: __neigh_notify (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 pid</code>
</li>
</ul>
</details>
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
