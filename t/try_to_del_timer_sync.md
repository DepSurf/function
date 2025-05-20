# Function: <code>try_to_del_timer_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec530)
Location: kernel/time/timer.c:1046
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff810ec530-ffffffff810ec5b4: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3c00)
Location: kernel/time/timer.c:1187
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff810f3c00-ffffffff810f3c84: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f9b50)
Location: kernel/time/timer.c:1197
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff810f9b50-ffffffff810f9bd0: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fbff0)
Location: kernel/time/timer.c:1171
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff810fbff0-ffffffff810fc06b: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811068d0)
Location: kernel/time/timer.c:1209
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff811068d0-ffffffff8110694b: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113240)
Location: kernel/time/timer.c:1217
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81113240-ffffffff811132bb: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111d560)
Location: kernel/time/timer.c:1216
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff8111d560-ffffffff8111d5db: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81128190)
Location: kernel/time/timer.c:1211
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81128190-ffffffff8112820d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81134130)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81134130-ffffffff811341ad: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811443e8)
Location: kernel/time/timer.c:1227
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81144330-ffffffff811443ad: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81140978)
Location: kernel/time/timer.c:1221
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff811408c0-ffffffff8114093d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141bc8)
Location: kernel/time/timer.c:1223
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81141a40-ffffffff81141abd: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81165038)
Location: kernel/time/timer.c:1223
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81164f80-ffffffff81164ffd: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81198c6d)
Location: kernel/time/timer.c:1276
Inline: True
Inline callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81198ba0-ffffffff81198c2d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d7190)
Location: kernel/time/timer.c:1442
Inline: False
Direct callers:
  - drivers/char/random.c:try_to_generate_entropy
```
**Symbols:**

```
ffffffff811d7190-ffffffff811d721d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811eb610)
Location: kernel/time/timer.c:1442
Inline: False
Direct callers:
  - drivers/char/random.c:try_to_generate_entropy
```
**Symbols:**

```
ffffffff811eb610-ffffffff811eb695: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81201640)
Location: kernel/time/timer.c:1442
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:lapic_offline
  - drivers/char/random.c:try_to_generate_entropy
```
**Symbols:**

```
ffffffff81201640-ffffffff812016c5: try_to_del_timer_sync (STB_GLOBAL)
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
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019ec78)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffff80001019ec78-ffff80001019ed14: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e757c)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
c03e757c-c03e7614: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001fc690)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
c0000000001fc690-c0000000001fc740: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012be0c)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffe00012be0c-ffffffe00012be6a: try_to_del_timer_sync (STB_GLOBAL)
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
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112c8e0)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff8112c8e0-ffffffff8112c95d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8111f150)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff8111f150-ffffffff8111f1cd: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112a600)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff8112a600-ffffffff8112a67d: try_to_del_timer_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_to_del_timer_sync(struct timer_list *timer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81137be0)
Location: kernel/time/timer.c:1215
Inline: False
Direct callers:
  - kernel/time/timer.c:del_timer_sync
```
**Symbols:**

```
ffffffff81137be0-ffffffff81137c5d: try_to_del_timer_sync (STB_GLOBAL)
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
