# Function: <code>xen_manage_runstate_time</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815bc5a0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff815bc5a0-ffffffff815bc76a: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff815f4e8a-ffffffff815f4ed9: xen_manage_runstate_time.cold.2 (STB_LOCAL)
ffffffff815f4c50-ffffffff815f4dd0: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8160fcea-ffffffff8160fd39: xen_manage_runstate_time.cold.2 (STB_LOCAL)
ffffffff8160fab0-ffffffff8160fc30: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81643b1a-ffffffff81643b69: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff816438e0-ffffffff81643a58: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816660ca-ffffffff81666119: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81665e90-ffffffff81666008: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81715808-ffffffff81715857: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81715590-ffffffff81715709: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81c04edc-ffffffff81c04f2b: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81731f60-ffffffff817320d9: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81bf6b66-ffffffff81bf6bb5: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81715a30-ffffffff81715baf: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81cf57b5-ffffffff81cf5818: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81792b40-ffffffff81792d58: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81ebd8d1-ffffffff81ebd935: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff818cb430-ffffffff818cb681: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff820946bb-ffffffff820946cf: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81a1c720-ffffffff81a1c9e1: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff82115430-ffffffff82115444: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81a658e0-ffffffff81a65bcb: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:85
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff821f30d0-ffffffff821f30e4: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81ab8140-ffffffff81ab842b: xen_manage_runstate_time (STB_GLOBAL)
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
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffff80001082f940)
Location: drivers/xen/time.c:84
Inline: False
```
**Symbols:**

```
ffff80001082f940-ffff80001082fb3c: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:86
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8162bdfa-ffffffff8162be49: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff8162bb00-ffffffff8162bc78: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81659f0a-ffffffff81659f59: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff81659cd0-ffffffff81659e48: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_manage_runstate_time(int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/time.c (0)
Location: drivers/xen/time.c:84
Inline: False
Direct callers:
  - drivers/xen/manage.c:xen_suspend
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816744da-ffffffff81674529: xen_manage_runstate_time.cold (STB_LOCAL)
ffffffff816742a0-ffffffff81674418: xen_manage_runstate_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
