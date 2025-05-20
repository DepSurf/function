# Function: <code>release_posix_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f1090)
Location: kernel/time/posix-timers.c:570
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:exit_itimers
```
**Symbols:**

```
ffffffff810f1090-ffffffff810f1105: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff810f80a0)
Location: kernel/time/posix-timers.c:570
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_create
```
**Symbols:**

```
ffffffff810f80a0-ffffffff810f8115: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81105a30)
Location: kernel/time/posix-timers.c:570
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:SyS_timer_create
```
**Symbols:**

```
ffffffff81105a30-ffffffff81105aa5: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81107c20)
Location: kernel/time/posix-timers.c:473
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81107c20-ffffffff81107c95: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81112da0)
Location: kernel/time/posix-timers.c:479
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:SyS_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81112da0-ffffffff81112e15: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8111e890)
Location: kernel/time/posix-timers.c:488
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8111e890-ffffffff8111e905: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112a060)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8112a060-ffffffff8112a0d5: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81134990)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81134990-ffffffff81134a05: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811409a0)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff811409a0-ffffffff81140a18: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114fb60)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8114fb60-ffffffff8114fbdb: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114bde0)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8114bde0-ffffffff8114be5b: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8114d290)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8114d290-ffffffff8114d30b: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81171390)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81171390-ffffffff8117140b: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811a5c00)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff811a5c00-ffffffff811a5c87: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff811e56e0)
Location: kernel/time/posix-timers.c:478
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff811e56e0-ffffffff811e5767: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffff8000101ab7f8)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__arm64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffff8000101ab7f8-ffff8000101ab8f4: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c03f637c)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
c03f637c-c03f63f8: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (c00000000020eb10)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
c00000000020eb10-c00000000020ec1c: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffe000136054)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__se_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffe000136054-ffffffe0001360da: release_posix_timer (STB_LOCAL)
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
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81139150)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81139150-ffffffff811391c8: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff8112bba0)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8112bba0-ffffffff8112bc18: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81136e70)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81136e70-ffffffff81136ee8: release_posix_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_posix_timer(struct k_itimer *tmr, int it_id_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-timers.c (ffffffff81143900)
Location: kernel/time/posix-timers.c:452
Inline: False
Direct callers:
  - kernel/time/posix-timers.c:exit_itimers
  - kernel/time/posix-timers.c:__ia32_sys_timer_delete
  - kernel/time/posix-timers.c:__x64_sys_timer_delete
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff81143900-ffffffff81143978: release_posix_timer (STB_LOCAL)
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
