# Function: <code>get_clock_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff810fa200)
Location: kernel/time/posix-clock.c:249
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_timer_gettime
  - kernel/time/posix-clock.c:pc_timer_delete
  - kernel/time/posix-clock.c:pc_timer_settime
  - kernel/time/posix-clock.c:pc_timer_create
  - kernel/time/posix-clock.c:pc_clock_adjtime
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
```
**Symbols:**

```
ffffffff810fa200-ffffffff810fa2c9: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811014a0)
Location: kernel/time/posix-clock.c:249
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_timer_settime
  - kernel/time/posix-clock.c:pc_timer_gettime
  - kernel/time/posix-clock.c:pc_timer_delete
  - kernel/time/posix-clock.c:pc_timer_create
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811014a0-ffffffff81101569: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81109160)
Location: kernel/time/posix-clock.c:249
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_timer_settime
  - kernel/time/posix-clock.c:pc_timer_gettime
  - kernel/time/posix-clock.c:pc_timer_delete
  - kernel/time/posix-clock.c:pc_timer_create
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81109160-ffffffff81109229: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff8110b260)
Location: kernel/time/posix-clock.c:217
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff8110b260-ffffffff8110b324: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811163a0)
Location: kernel/time/posix-clock.c:217
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811163a0-ffffffff81116464: get_clock_desc (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff81122c50)
Location: kernel/time/posix-clock.c:217
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81122c50-ffffffff81122d04: get_clock_desc.isra.2 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff8112e330)
Location: kernel/time/posix-clock.c:204
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff8112e330-ffffffff8112e3e4: get_clock_desc.isra.2 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff81138de0)
Location: kernel/time/posix-clock.c:204
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81138de0-ffffffff81138e96: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff81144b00)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81144b00-ffffffff81144bb6: get_clock_desc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff811541e0)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811541e0-ffffffff81154294: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81150460)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81150460-ffffffff81150514: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81151890)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81151890-ffffffff81151944: get_clock_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81175cd0-ffffffff81175d96: get_clock_desc (STB_LOCAL)
ffffffff81cb1d91-ffffffff81cb1da6: get_clock_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811aace0-ffffffff811aadc3: get_clock_desc (STB_LOCAL)
ffffffff81e6333d-ffffffff81e63352: get_clock_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811eae80-ffffffff811eaf63: get_clock_desc (STB_LOCAL)
ffffffff8205bbb3-ffffffff8205bbc8: get_clock_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff811ff5d0-ffffffff811ff6b6: get_clock_desc (STB_LOCAL)
ffffffff820da3b5-ffffffff820da3ca: get_clock_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/posix-clock.c (0)
Location: kernel/time/posix-clock.c:217
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81215a50-ffffffff81215b39: get_clock_desc (STB_LOCAL)
ffffffff821b5d2f-ffffffff821b5d44: get_clock_desc.cold (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffff8000101af168)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffff8000101af168-ffff8000101af228: get_clock_desc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_clock_desc(const clockid_t id, struct posix_clock_desc *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (c03fa080)
Location: kernel/time/posix-clock.c:199
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
c03fa080-c03fa10c: get_clock_desc (STB_LOCAL)
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
In kernel/time/posix-clock.c (c000000000213910)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
c000000000213910-c0000000002139e4: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffe00013890a)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffe00013890a-ffffffe00013898c: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff8113d2b0)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff8113d2b0-ffffffff8113d366: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff8112fe00)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff8112fe00-ffffffff8112feb6: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff8113afd0)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff8113afd0-ffffffff8113b086: get_clock_desc.isra.0 (STB_LOCAL)
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
In kernel/time/posix-clock.c (ffffffff81147a80)
Location: kernel/time/posix-clock.c:199
Inline: True
Direct callers:
  - kernel/time/posix-clock.c:pc_clock_settime
  - kernel/time/posix-clock.c:pc_clock_getres
  - kernel/time/posix-clock.c:pc_clock_gettime
  - kernel/time/posix-clock.c:pc_clock_adjtime
```
**Symbols:**

```
ffffffff81147a80-ffffffff81147b36: get_clock_desc.isra.0 (STB_LOCAL)
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
