# Function: <code>kobj_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff8154ef10)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:add_disk
```
**Symbols:**

```
ffffffff8154ef10-ffffffff8154f08c: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff815a0cf0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815a0cf0-ffffffff815a0e65: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff815cf360)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815cf360-ffffffff815cf4d5: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff815e3df0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff815e3df0-ffffffff815e3f67: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff8164b0b0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8164b0b0-ffffffff8164b227: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816866d0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816866d0-ffffffff81686839: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816a6370)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816a6370-ffffffff816a64d9: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816df3b0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816df3b0-ffffffff816df54b: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff81703600)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81703600-ffffffff8170379b: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff817bd9a0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff817bd9a0-ffffffff817bdb34: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff817d26f0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff817d26f0-ffffffff817d2884: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff817b6110)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff817b6110-ffffffff817b629e: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff8183f6f0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff8183f6f0-ffffffff8183f8aa: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff819827f0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff819827f0-ffffffff819829d4: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff81af0680)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff81af0680-ffffffff81af0864: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff81b3e7d0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff81b3e7d0-ffffffff81b3e9a8: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff81b965f0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
```
**Symbols:**

```
ffffffff81b965f0-ffffffff81b967c8: kobj_map (STB_GLOBAL)
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
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffff8000108ef288)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffff8000108ef288-ffff8000108ef400: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (c09dca04)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c09dca04-c09dcb6c: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (c000000000988250)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c000000000988250-c00000000098845c: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffe000581b64)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffe000581b64-ffffffe000581cb4: kobj_map (STB_GLOBAL)
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
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816c8d50)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816c8d50-ffffffff816c8eeb: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816a4080)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816a4080-ffffffff816a421b: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff816f72c0)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff816f72c0-ffffffff816f745b: kobj_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kobj_map(struct kobj_map *domain, dev_t dev, long unsigned int range, struct module *module, kobj_probe_t *probe, int (*lock)(dev_t, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/map.c (ffffffff81711b60)
Location: drivers/base/map.c:32
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_add
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81711b60-ffffffff81711cfb: kobj_map (STB_GLOBAL)
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
