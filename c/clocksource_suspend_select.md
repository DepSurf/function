# Function: <code>clocksource_suspend_select</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811261b0)
Location: kernel/time/clocksource.c:488
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff811261b0-ffffffff81126226: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81130be0)
Location: kernel/time/clocksource.c:488
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff81130be0-ffffffff81130c4a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113cb20)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff8113cb20-ffffffff8113cb8a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff8114b990-ffffffff8114ba35: clocksource_suspend_select (STB_LOCAL)
ffffffff8114ca15-ffffffff8114ca2a: clocksource_suspend_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff81147df0-ffffffff81147e95: clocksource_suspend_select (STB_LOCAL)
ffffffff81be394c-ffffffff81be3961: clocksource_suspend_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:596
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff81148e80-ffffffff81148f25: clocksource_suspend_select (STB_LOCAL)
ffffffff81bd581c-ffffffff81bd5831: clocksource_suspend_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:708
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff8116cb40-ffffffff8116cbe5: clocksource_suspend_select (STB_LOCAL)
ffffffff81cb1637-ffffffff81cb164c: clocksource_suspend_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:714
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff811a0b10-ffffffff811a0bbf: clocksource_suspend_select (STB_LOCAL)
ffffffff81e62c11-ffffffff81e62c26: clocksource_suspend_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811dfb00)
Location: kernel/time/clocksource.c:733
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff811dfb00-ffffffff811dfbb9: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f4000)
Location: kernel/time/clocksource.c:744
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff811f4000-ffffffff811f40b9: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120a140)
Location: kernel/time/clocksource.c:767
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff8120a140-ffffffff8120a1f9: clocksource_suspend_select (STB_LOCAL)
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
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a6c40)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffff8000101a6c40-ffff8000101a6cc4: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f1c88)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
c03f1c88-c03f1d08: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c000000000209410)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
c000000000209410-c0000000002094d4: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe000132d4c)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffe000132d4c-ffffffe000132dc4: clocksource_suspend_select (STB_LOCAL)
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
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811352d0)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff811352d0-ffffffff8113533a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81127d30)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff81127d30-ffffffff81127d9a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81132ff0)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff81132ff0-ffffffff8113305a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clocksource_suspend_select(bool fallback);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8113fa10)
Location: kernel/time/clocksource.c:495
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
```
**Symbols:**

```
ffffffff8113fa10-ffffffff8113fa7a: clocksource_suspend_select (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
