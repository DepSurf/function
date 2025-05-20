# Function: <code>tick_do_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff810fce00)
Location: kernel/time/tick-broadcast.c:259
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff810fce00-ffffffff810fce93: tick_do_broadcast.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81104160)
Location: kernel/time/tick-broadcast.c:259
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81104160-ffffffff811041f0: tick_do_broadcast.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110b890)
Location: kernel/time/tick-broadcast.c:259
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8110b890-ffffffff8110b91d: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110d8d0)
Location: kernel/time/tick-broadcast.c:262
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8110d8d0-ffffffff8110d95c: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81118b50)
Location: kernel/time/tick-broadcast.c:262
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81118b50-ffffffff81118be2: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811256d0)
Location: kernel/time/tick-broadcast.c:262
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff811256d0-ffffffff8112576c: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81130dc0)
Location: kernel/time/tick-broadcast.c:258
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81130dc0-ffffffff81130e5c: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8113b920)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8113b920-ffffffff8113b9bb: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81147530)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81147530-ffffffff811475cb: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81157240)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81157240-ffffffff811572d1: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81153310)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81153310-ffffffff811533a1: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81154710)
Location: kernel/time/tick-broadcast.c:276
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81154710-ffffffff811547a1: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81179140)
Location: kernel/time/tick-broadcast.c:345
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81179140-ffffffff811791fa: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811ae7a0)
Location: kernel/time/tick-broadcast.c:345
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff811ae7a0-ffffffff811ae86d: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811ef0e0)
Location: kernel/time/tick-broadcast.c:345
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff811ef0e0-ffffffff811ef1ad: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81203640)
Location: kernel/time/tick-broadcast.c:346
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81203640-ffffffff8120370d: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81219c00)
Location: kernel/time/tick-broadcast.c:346
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff81219c00-ffffffff81219ccd: tick_do_broadcast (STB_LOCAL)
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
In kernel/time/tick-broadcast.c (ffff8000101b2728)
Location: kernel/time/tick-broadcast.c:264
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffff8000101b2728-ffff8000101b2824: tick_do_broadcast.constprop.0 (STB_LOCAL)
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
In kernel/time/tick-broadcast.c (c03fca6c)
Location: kernel/time/tick-broadcast.c:264
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
c03fca6c-c03fcb34: tick_do_broadcast.constprop.0 (STB_LOCAL)
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
In kernel/time/tick-broadcast.c (c0000000002178a0)
Location: kernel/time/tick-broadcast.c:264
Inline: True
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
c0000000002178a0-c0000000002179b8: tick_do_broadcast.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8113fb50)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8113fb50-ffffffff8113fbeb: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811328d0)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff811328d0-ffffffff8113296b: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8113da00)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8113da00-ffffffff8113da9b: tick_do_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tick_do_broadcast(struct cpumask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8114a510)
Location: kernel/time/tick-broadcast.c:264
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
```
**Symbols:**

```
ffffffff8114a510-ffffffff8114a5ab: tick_do_broadcast (STB_LOCAL)
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
