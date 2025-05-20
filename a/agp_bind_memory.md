# Function: <code>agp_bind_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151da70)
Location: drivers/char/agp/generic.c:411
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8151da70-ffffffff8151db47: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81570840)
Location: drivers/char/agp/generic.c:411
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff81570840-ffffffff81570917: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159cf00)
Location: drivers/char/agp/generic.c:411
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8159cf00-ffffffff8159cfd7: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815b0fb0)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff815b0fb0-ffffffff815b1082: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81617b50)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff81617b50-ffffffff81617c2e: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff81652207-ffffffff81652221: agp_bind_memory.cold.19 (STB_LOCAL)
ffffffff81651650-ffffffff8165171c: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166f9ee)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816703db-ffffffff816703f5: agp_bind_memory.cold.18 (STB_LOCAL)
ffffffff8166f9a0-ffffffff8166fa6c: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816a5580)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816a5e33-ffffffff816a5e4d: agp_bind_memory.cold (STB_LOCAL)
ffffffff816a5530-ffffffff816a5607: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816c82b0)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816c8b63-ffffffff816c8b7d: agp_bind_memory.cold (STB_LOCAL)
ffffffff816c8260-ffffffff816c8337: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8177d3f5-ffffffff8177d40f: agp_bind_memory.cold (STB_LOCAL)
ffffffff8177bf70-ffffffff8177c047: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff81c08e85-ffffffff81c08e9f: agp_bind_memory.cold (STB_LOCAL)
ffffffff817950c0-ffffffff8179519b: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff81bfaa38-ffffffff81bfaa52: agp_bind_memory.cold (STB_LOCAL)
ffffffff81777d70-ffffffff81777e4b: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff81cfb735-ffffffff81cfb779: agp_bind_memory.cold (STB_LOCAL)
ffffffff817fe340-ffffffff817fe43b: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff81ec3f4e-ffffffff81ec3f92: agp_bind_memory.cold (STB_LOCAL)
ffffffff8193d910-ffffffff8193d9fe: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff820968a3-ffffffff820968cd: agp_bind_memory.cold (STB_LOCAL)
ffffffff81a9e7e0-ffffffff81a9e8e5: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff821177e2-ffffffff8211780c: agp_bind_memory.cold (STB_LOCAL)
ffffffff81aea160-ffffffff81aea265: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:408
Inline: False
```
**Symbols:**

```
ffffffff821f5557-ffffffff821f5581: agp_bind_memory.cold (STB_LOCAL)
ffffffff81b3d5f0-ffffffff81b3d6f5: agp_bind_memory (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c000000000955870)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
c000000000955870-c000000000955a28: agp_bind_memory (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8168dd00)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8168e5b3-ffffffff8168e5cd: agp_bind_memory.cold (STB_LOCAL)
ffffffff8168dcb0-ffffffff8168dd87: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166b6f0)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8166bfa3-ffffffff8166bfbd: agp_bind_memory.cold (STB_LOCAL)
ffffffff8166b6a0-ffffffff8166b777: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816bbf70)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816bc823-ffffffff816bc83d: agp_bind_memory.cold (STB_LOCAL)
ffffffff816bbf20-ffffffff816bbff7: agp_bind_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int agp_bind_memory(struct agp_memory *curr, off_t pg_start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816d6540)
Location: drivers/char/agp/generic.c:407
Inline: True
Direct callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816d6df3-ffffffff816d6e0d: agp_bind_memory.cold (STB_LOCAL)
ffffffff816d64f0-ffffffff816d65c5: agp_bind_memory (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
