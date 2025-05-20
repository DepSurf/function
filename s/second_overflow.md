# Function: <code>second_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int second_overflow(long unsigned int secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810f6e60)
Location: kernel/time/ntp.c:393
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff810f6e60-ffffffff810f716c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810fdfe0)
Location: kernel/time/ntp.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff810fdfe0-ffffffff810fe2ac: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81100dd0)
Location: kernel/time/ntp.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff81100dd0-ffffffff8110109c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81102f10)
Location: kernel/time/ntp.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff81102f10-ffffffff811031e9: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8110e0a0)
Location: kernel/time/ntp.c:399
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff8110e0a0-ffffffff8110e37f: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:399
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:update_wall_time
  - kernel/time/timekeeping.c:update_wall_time
```
**Symbols:**

```
ffffffff8111a4d7-ffffffff8111a528: second_overflow.cold.6 (STB_LOCAL)
ffffffff81119aa0-ffffffff81119d4a: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff811259d7-ffffffff81125a26: second_overflow.cold.5 (STB_LOCAL)
ffffffff81124fb0-ffffffff8112525a: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8113043a-ffffffff8113048b: second_overflow.cold (STB_LOCAL)
ffffffff8112fa10-ffffffff8112fcdc: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8113c37a-ffffffff8113c3cb: second_overflow.cold (STB_LOCAL)
ffffffff8113b950-ffffffff8113bc1c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8114b471-ffffffff8114b4c2: second_overflow.cold (STB_LOCAL)
ffffffff8114acd0-ffffffff8114af9c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81be389b-ffffffff81be38ec: second_overflow.cold (STB_LOCAL)
ffffffff81147100-ffffffff811473cc: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81bd571b-ffffffff81bd576c: second_overflow.cold (STB_LOCAL)
ffffffff81148240-ffffffff811484f5: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81cb140f-ffffffff81cb14a6: second_overflow.cold (STB_LOCAL)
ffffffff8116bda0-ffffffff8116c0a6: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81e629ae-ffffffff81e62a45: second_overflow.cold (STB_LOCAL)
ffffffff8119fd30-ffffffff811a0022: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8205b7ea-ffffffff8205b830: second_overflow.cold (STB_LOCAL)
ffffffff811deae0-ffffffff811dee1b: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff820da0a4-ffffffff820da0ea: second_overflow.cold (STB_LOCAL)
ffffffff811f2fb0-ffffffff811f32f4: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff821b59a3-ffffffff821b59e9: second_overflow.cold (STB_LOCAL)
ffffffff812090f0-ffffffff81209434: second_overflow (STB_GLOBAL)
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
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffff8000101a5e08)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffff8000101a5e08-ffff8000101a60cc: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c03f0d60)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
c03f0d60-c03f10b8: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (c000000000207ba0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
c000000000207ba0-c00000000020808c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffe000131fc4)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffe000131fc4-ffffffe0001321fc: second_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81134b2a-ffffffff81134b7b: second_overflow.cold (STB_LOCAL)
ffffffff81134100-ffffffff811343cc: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8112758a-ffffffff811275db: second_overflow.cold (STB_LOCAL)
ffffffff81126b60-ffffffff81126e2c: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8113284a-ffffffff8113289b: second_overflow.cold (STB_LOCAL)
ffffffff81131e20-ffffffff811320ec: second_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int second_overflow(time64_t secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/ntp.c (0)
Location: kernel/time/ntp.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8113f26a-ffffffff8113f2bb: second_overflow.cold (STB_LOCAL)
ffffffff8113e840-ffffffff8113eb0c: second_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int secs</code> ➡️ <code>time64_t secs</code>
</li>
</ul>
</details>
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
