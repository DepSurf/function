# Function: <code>hibernation_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810cefa5)
Location: kernel/power/hibernate.c:68
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810cf390-ffffffff810cf3b0: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d3a45)
Location: kernel/power/hibernate.c:69
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810d3e20-ffffffff810d3e40: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810da5d5)
Location: kernel/power/hibernate.c:69
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810da9b0-ffffffff810da9d0: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810d97b5)
Location: kernel/power/hibernate.c:71
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810d9a90-ffffffff810d9ab0: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e19d0)
Location: kernel/power/hibernate.c:71
Inline: False
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810e19d0-ffffffff810e1a0c: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810e9fb0)
Location: kernel/power/hibernate.c:71
Inline: False
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810e9fb0-ffffffff810e9fec: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810f55d0)
Location: kernel/power/hibernate.c:71
Inline: False
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810f55d0-ffffffff810f560c: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810fdae0)
Location: kernel/power/hibernate.c:69
Inline: False
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810fdae0-ffffffff810fdb1c: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81109e75)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110a100-ffffffff8110a127: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81114b85)
Location: kernel/power/hibernate.c:82
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff81114d10-ffffffff81114d37: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81111f08)
Location: kernel/power/hibernate.c:82
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff811116d0-ffffffff811116f7: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81112928)
Location: kernel/power/hibernate.c:82
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff81112120-ffffffff81112147: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff8113295c)
Location: kernel/power/hibernate.c:83
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff81132140-ffffffff81132172: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811548a4)
Location: kernel/power/hibernate.c:82
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff81153e40-ffffffff81153e8d: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81184382)
Location: kernel/power/hibernate.c:82
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff811833d0-ffffffff8118341d: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194f8f)
Location: kernel/power/hibernate.c:83
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff81194240-ffffffff8119428d: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a396f)
Location: kernel/power/hibernate.c:83
Inline: True
Inline callers:
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
  - kernel/power/user.c:is_hibernate_resume_dev
```
**Symbols:**

```
ffffffff811a2c30-ffffffff811a2c7d: hibernation_available (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:464
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bc250)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
c03bc570-c03bc5b4: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:464
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (0)
Location: include/linux/suspend.h:464
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811020d5)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff81102360-ffffffff81102387: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff810f3365)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff810f35f0-ffffffff810f3617: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81100345)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff811005d0-ffffffff811005f7: hibernation_available (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool hibernation_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff8110b6e5)
Location: kernel/power/hibernate.c:70
Inline: True
Inline callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
Direct callers:
  - kernel/power/main.c:state_show
  - kernel/power/user.c:snapshot_open
```
**Symbols:**

```
ffffffff8110b970-ffffffff8110b997: hibernation_available (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
