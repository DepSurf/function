# Function: <code>fb_modesetting_disabled</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fb_modesetting_disabled(const char *drvname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819367b0)
Location: drivers/video/fbdev/core/fbmem.c:1853
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
```
**Symbols:**

```
ffffffff819367b0-ffffffff819367f7: fb_modesetting_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fb_modesetting_disabled(const char *drvname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197a7e0)
Location: drivers/video/fbdev/core/fbmem.c:1717
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
```
**Symbols:**

```
ffffffff8197a7e0-ffffffff8197a827: fb_modesetting_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fb_modesetting_disabled(const char *drvname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c3f50)
Location: drivers/video/fbdev/core/fbmem.c:649
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
```
**Symbols:**

```
ffffffff819c3f50-ffffffff819c3f97: fb_modesetting_disabled (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
