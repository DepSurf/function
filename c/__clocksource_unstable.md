# Function: <code>__clocksource_unstable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810f82e2)
Location: kernel/time/clocksource.c:139
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810ff552)
Location: kernel/time/clocksource.c:139
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811023c2)
Location: kernel/time/clocksource.c:140
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811044f0)
Location: kernel/time/clocksource.c:140
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811044f0-ffffffff8110453a: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110f570)
Location: kernel/time/clocksource.c:140
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8110f570-ffffffff8110f5bd: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8111af50)
Location: kernel/time/clocksource.c:159
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8111af50-ffffffff8111afb2: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81126590)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff81126590-ffffffff811265f2: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81130fc0)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff81130fc0-ffffffff81131022: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113cf00)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8113cf00-ffffffff8113cf62: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8114bbe0)
Location: kernel/time/clocksource.c:145
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8114bbe0-ffffffff8114bc42: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81148040)
Location: kernel/time/clocksource.c:145
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff81148040-ffffffff811480a2: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81148f30)
Location: kernel/time/clocksource.c:152
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff81148f30-ffffffff81148f95: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8116cbf0)
Location: kernel/time/clocksource.c:160
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8116cbf0-ffffffff8116cc55: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811a0bc0)
Location: kernel/time/clocksource.c:166
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811a0bc0-ffffffff811a0c49: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811dfbd0)
Location: kernel/time/clocksource.c:166
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811dfbd0-ffffffff811dfc59: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f40d0)
Location: kernel/time/clocksource.c:169
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811f40d0-ffffffff811f4159: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120a210)
Location: kernel/time/clocksource.c:171
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8120a210-ffffffff8120a299: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811356b0)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811356b0-ffffffff81135712: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81128110)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff81128110-ffffffff81128172: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811333d0)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff811333d0-ffffffff81133432: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __clocksource_unstable(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113fdf0)
Location: kernel/time/clocksource.c:145
Inline: True
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
**Symbols:**

```
ffffffff8113fdf0-ffffffff8113fe52: __clocksource_unstable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
