# Function: <code>crypto_shash_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3660)
Location: crypto/shash.c:98
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_superblock_csum
  - fs/jbd2/journal.c:journal_get_superblock
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - crypto/shash.c:shash_finup_unaligned
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_compat_update
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813a3660-ffffffff813a375d: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813df7c0)
Location: crypto/shash.c:98
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813df7c0-ffffffff813df8cf: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f7d50)
Location: crypto/shash.c:98
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813f7d50-ffffffff813f7e5f: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81404200)
Location: crypto/shash.c:99
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81404200-ffffffff81404317: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142cad0)
Location: crypto/shash.c:107
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8142cad0-ffffffff8142cbf9: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145f730)
Location: crypto/shash.c:107
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8145f730-ffffffff8145f862: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d2a0)
Location: crypto/shash.c:115
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8147d2a0-ffffffff8147d2c7: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab590)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814ab590-ffffffff814ab5b7: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6260)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814c6260-ffffffff814c6287: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525a4f)
Location: crypto/shash.c:109
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/crc-t10dif.c:crc_t10dif
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff815251a0-ffffffff815251c7: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154297f)
Location: crypto/shash.c:109
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/crc-t10dif.c:crc_t10dif_update
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81542090-ffffffff815420b7: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154b01f)
Location: crypto/shash.c:121
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/crc-t10dif.c:crc_t10dif_update
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8154a730-ffffffff8154a757: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab7ff)
Location: crypto/shash.c:121
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/crc-t10dif.c:crc_t10dif_update
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff815aaf10-ffffffff815aaf37: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff816530c4)
Location: crypto/shash.c:121
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_memcpy
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/crc-t10dif.c:crc_t10dif_update
  - lib/crc64-rocksoft.c:crc64_rocksoft_update
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81652620-ffffffff8165265b: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170cda4)
Location: crypto/shash.c:111
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/crc-t10dif.c:crc_t10dif_update
  - lib/crc64-rocksoft.c:crc64_rocksoft_update
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff8170c4e0-ffffffff8170c51b: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746510)
Location: crypto/shash.c:120
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_update
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/crc-t10dif.c:crc_t10dif
  - lib/crc64-rocksoft.c:crc64_rocksoft
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81746510-ffffffff81746576: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788950)
Location: crypto/shash.c:61
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:journal_check_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/ahash.c:shash_ahash_finup
  - crypto/ahash.c:shash_ahash_update
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/crc-t10dif.c:crc_t10dif
  - lib/crc64-rocksoft.c:crc64_rocksoft
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81788950-ffffffff8178898a: crypto_shash_update (STB_GLOBAL)
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
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1370)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffff8000105c1370-ffff8000105c13ec: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076ebc8)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/extents.c:ext4_chksum
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c076ebc8-c076ec04: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749780)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c000000000749780-c0000000007497e4: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe0004060da)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_superblock_csum
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffe0004060da-ffffffe00040613c: crypto_shash_update (STB_GLOBAL)
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
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be840)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814be840-ffffffff814be867: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af260)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814af260-ffffffff814af287: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ba8d0)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814ba8d0-ffffffff814ba8f7: crypto_shash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_shash_update(struct shash_desc *desc, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3380)
Location: crypto/shash.c:110
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
  - fs/ext4/extents.c:ext4_extent_block_csum
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_update
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe_contents
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814d3380-ffffffff814d33a7: crypto_shash_update (STB_GLOBAL)
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
