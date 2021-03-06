# Created by: Timothy Beyer <beyert@cs.ucr.edu>
# $FreeBSD$

PORTNAME=	racer
DISTVERSION=	2.1.33
CATEGORIES=	devel
MASTER_SITES=	CRATESIO
DISTFILES=	${CARGO_DIST_SUBDIR}/${DISTNAME}${EXTRACT_SUFX}

MAINTAINER=	rust@FreeBSD.org
COMMENT=	Rust code completion helper

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE-MIT

USES=		cargo
CARGO_CRATES=	aho-corasick-0.7.10 \
		annotate-snippets-0.6.1 \
		ansi_term-0.11.0 \
		atty-0.2.14 \
		autocfg-1.0.0 \
		bitflags-1.2.1 \
		block-buffer-0.7.3 \
		block-padding-0.1.5 \
		byte-tools-0.3.1 \
		byteorder-1.3.4 \
		cfg-if-0.1.10 \
		clap-2.33.0 \
		cloudabi-0.0.3 \
		crossbeam-deque-0.7.3 \
		crossbeam-epoch-0.8.2 \
		crossbeam-queue-0.1.2 \
		crossbeam-utils-0.6.6 \
		crossbeam-utils-0.7.2 \
		derive_more-0.99.5 \
		digest-0.8.1 \
		either-1.5.3 \
		ena-0.13.1 \
		env_logger-0.7.1 \
		fake-simd-0.1.2 \
		generic-array-0.12.3 \
		getopts-0.2.21 \
		getrandom-0.1.14 \
		hermit-abi-0.1.10 \
		humantime-1.3.0 \
		humantime-2.0.0 \
		indexmap-1.3.2 \
		itoa-0.4.5 \
		jobserver-0.1.21 \
		lazy_static-1.4.0 \
		lazycell-1.2.1 \
		libc-0.2.68 \
		lock_api-0.3.3 \
		log-0.4.8 \
		maybe-uninit-2.0.0 \
		md-5-0.8.0 \
		measureme-0.7.1 \
		memchr-2.3.3 \
		memmap-0.7.0 \
		memoffset-0.5.4 \
		num_cpus-1.12.0 \
		opaque-debug-0.2.3 \
		parking_lot-0.9.0 \
		parking_lot-0.10.0 \
		parking_lot_core-0.6.2 \
		parking_lot_core-0.7.0 \
		ppv-lite86-0.2.6 \
		proc-macro2-1.0.10 \
		quick-error-1.2.3 \
		quote-1.0.3 \
		racer-2.1.32 \
		racer-cargo-metadata-0.1.1 \
		racer-interner-0.1.0 \
		racer-testutils-0.1.0 \
		rand-0.7.3 \
		rand_chacha-0.2.2 \
		rand_core-0.5.1 \
		rand_hc-0.2.0 \
		redox_syscall-0.1.56 \
		regex-1.3.6 \
		regex-syntax-0.6.17 \
		remove_dir_all-0.5.2 \
		rls-span-0.5.2 \
		rustc-ap-arena-651.0.0 \
		rustc-ap-arena-654.0.0 \
		rustc-ap-graphviz-651.0.0 \
		rustc-ap-graphviz-654.0.0 \
		rustc-ap-rustc_ast-651.0.0 \
		rustc-ap-rustc_ast-654.0.0 \
		rustc-ap-rustc_ast_pretty-651.0.0 \
		rustc-ap-rustc_ast_pretty-654.0.0 \
		rustc-ap-rustc_data_structures-651.0.0 \
		rustc-ap-rustc_data_structures-654.0.0 \
		rustc-ap-rustc_errors-651.0.0 \
		rustc-ap-rustc_errors-654.0.0 \
		rustc-ap-rustc_feature-651.0.0 \
		rustc-ap-rustc_feature-654.0.0 \
		rustc-ap-rustc_fs_util-651.0.0 \
		rustc-ap-rustc_fs_util-654.0.0 \
		rustc-ap-rustc_index-651.0.0 \
		rustc-ap-rustc_index-654.0.0 \
		rustc-ap-rustc_lexer-651.0.0 \
		rustc-ap-rustc_lexer-654.0.0 \
		rustc-ap-rustc_macros-651.0.0 \
		rustc-ap-rustc_macros-654.0.0 \
		rustc-ap-rustc_parse-651.0.0 \
		rustc-ap-rustc_parse-654.0.0 \
		rustc-ap-rustc_session-651.0.0 \
		rustc-ap-rustc_session-654.0.0 \
		rustc-ap-rustc_span-651.0.0 \
		rustc-ap-rustc_span-654.0.0 \
		rustc-ap-rustc_target-651.0.0 \
		rustc-ap-rustc_target-654.0.0 \
		rustc-ap-serialize-651.0.0 \
		rustc-ap-serialize-654.0.0 \
		rustc-hash-1.1.0 \
		rustc-rayon-0.3.0 \
		rustc-rayon-core-0.3.0 \
		rustc_version-0.2.3 \
		ryu-1.0.3 \
		scoped-tls-1.0.0 \
		scopeguard-1.1.0 \
		semver-0.9.0 \
		semver-parser-0.7.0 \
		serde-1.0.105 \
		serde_derive-1.0.105 \
		serde_json-1.0.50 \
		sha-1-0.8.2 \
		smallvec-0.6.13 \
		smallvec-1.2.0 \
		stable_deref_trait-1.1.1 \
		strsim-0.8.0 \
		syn-1.0.17 \
		synstructure-0.12.3 \
		tempfile-3.1.0 \
		termcolor-1.1.0 \
		termize-0.1.1 \
		textwrap-0.11.0 \
		thread_local-1.0.1 \
		typenum-1.12.0 \
		unicode-normalization-0.1.12 \
		unicode-width-0.1.7 \
		unicode-xid-0.2.0 \
		vec_map-0.8.1 \
		wasi-0.9.0+wasi-snapshot-preview1 \
		winapi-0.3.8 \
		winapi-i686-pc-windows-gnu-0.4.0 \
		winapi-util-0.1.4 \
		winapi-x86_64-pc-windows-gnu-0.4.0
MAKE_ENV=	RUSTC_BOOTSTRAP=1
PLIST_FILES=	bin/racer

.include <bsd.port.mk>
