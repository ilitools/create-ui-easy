{
  "name": "create-ui-easy",
  "version": "1.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "create-ui-easy",
      "version": "1.0.0",
      "license": "MIT",
      "dependencies": {
        "axios": "^1.7.7",
        "commander": "^12.1.0",
        "download-git-repo": "^3.0.2",
        "fs-extra": "^11.2.0",
        "lodash-es": "^4.17.21",
        "mkcert": "^3.2.0",
        "ora": "^8.1.1",
        "prompts": "^2.4.2",
        "rimraf": "^6.0.1"
      },
      "bin": {
        "create-ui-easy": "index.js"
      },
      "devDependencies": {
        "chalk": "^5.3.0",
        "figlet": "^1.8.0",
        "release-it": "^17.10.0",
        "unbuild": "^2.0.0"
      }
    },
    "node_modules/@ampproject/remapping": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/@ampproject/remapping/-/remapping-2.3.0.tgz",
      "integrity": "sha512-30iZtAPgz+LTIYoeivqYo853f02jBYSd5uGnGpkFV0M3xOt9aN73erkgYAmZU43x4VfqcnLxW9Kpg3R5LC4YYw==",
      "dev": true,
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/code-frame": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/code-frame/-/code-frame-7.26.0.tgz",
      "integrity": "sha512-INCKxTtbXtcNbUZ3YXutwMpEleqttcswhAdee7dhuoVrD2cnuc3PqtERBtxkX5nziX9vnBL8WXmSGwv8CuPV6g==",
      "dev": true,
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.25.9",
        "js-tokens": "^4.0.0",
        "picocolors": "^1.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/compat-data": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/compat-data/-/compat-data-7.26.0.tgz",
      "integrity": "sha512-qETICbZSLe7uXv9VE8T/RWOdIE5qqyTucOt4zLYMafj2MRO271VGgLd4RACJMeBO37UPWhXiKMBk7YlJ0fOzQA==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/core": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/core/-/core-7.26.0.tgz",
      "integrity": "sha512-i1SLeK+DzNnQ3LL/CswPCa/E5u4lh1k6IAEphON8F+cXt0t9euTshDru0q7/IqMa1PMPz5RnHuHscF8/ZJsStg==",
      "dev": true,
      "dependencies": {
        "@ampproject/remapping": "^2.2.0",
        "@babel/code-frame": "^7.26.0",
        "@babel/generator": "^7.26.0",
        "@babel/helper-compilation-targets": "^7.25.9",
        "@babel/helper-module-transforms": "^7.26.0",
        "@babel/helpers": "^7.26.0",
        "@babel/parser": "^7.26.0",
        "@babel/template": "^7.25.9",
        "@babel/traverse": "^7.25.9",
        "@babel/types": "^7.26.0",
        "convert-source-map": "^2.0.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.2",
        "json5": "^2.2.3",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/babel"
      }
    },
    "node_modules/@babel/core/node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmmirror.com/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/@babel/generator": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/generator/-/generator-7.26.0.tgz",
      "integrity": "sha512-/AIkAmInnWwgEAJGQr9vY0c66Mj6kjkE2ZPB1PurTRaRAh3U+J45sAQMjQDJdh4WbR3l0x5xkimXBKyBXXAu2w==",
      "dev": true,
      "dependencies": {
        "@babel/parser": "^7.26.0",
        "@babel/types": "^7.26.0",
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.25",
        "jsesc": "^3.0.2"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/helper-compilation-targets/-/helper-compilation-targets-7.25.9.tgz",
      "integrity": "sha512-j9Db8Suy6yV/VHa4qzrj9yZfZxhLWQdVnRlXxmKLYlhWUVB1sB2G5sxuWYXk/whHD9iW76PmNzxZ4UCnTQTVEQ==",
      "dev": true,
      "dependencies": {
        "@babel/compat-data": "^7.25.9",
        "@babel/helper-validator-option": "^7.25.9",
        "browserslist": "^4.24.0",
        "lru-cache": "^5.1.1",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets/node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmmirror.com/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/@babel/helper-module-imports": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/helper-module-imports/-/helper-module-imports-7.25.9.tgz",
      "integrity": "sha512-tnUA4RsrmflIM6W6RFTLFSXITtl0wKjgpnLgXyowocVPrbYrLUXSBXDgTs8BlbmIzIdlBySRQjINYs2BAkiLtw==",
      "dev": true,
      "dependencies": {
        "@babel/traverse": "^7.25.9",
        "@babel/types": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-transforms": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/helper-module-transforms/-/helper-module-transforms-7.26.0.tgz",
      "integrity": "sha512-xO+xu6B5K2czEnQye6BHA7DolFFmS3LB7stHZFaOLb1pAwO1HWLS8fXA+eh0A2yIvltPVmx3eNNDBJA2SLHXFw==",
      "dev": true,
      "dependencies": {
        "@babel/helper-module-imports": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9",
        "@babel/traverse": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/@babel/helper-string-parser": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/helper-string-parser/-/helper-string-parser-7.25.9.tgz",
      "integrity": "sha512-4A/SCr/2KLd5jrtOMFzaKjVtAei3+2r/NChoBNoZ3EyP/+GlhoaEGoWOZUmFmoITP7zOJyHIMm+DYRd8o3PvHA==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-identifier": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/helper-validator-identifier/-/helper-validator-identifier-7.25.9.tgz",
      "integrity": "sha512-Ed61U6XJc3CVRfkERJWDz4dJwKe7iLmmJsbOGu9wSloNSFttHV0I8g6UAgb7qnK5ly5bGLPd4oXZlxCdANBOWQ==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-option": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/helper-validator-option/-/helper-validator-option-7.25.9.tgz",
      "integrity": "sha512-e/zv1co8pp55dNdEcCynfj9X7nyUKUXoUEwfXqaZt0omVOmDe9oOTdKStH4GmAw6zxMFs50ZayuMfHDKlO7Tfw==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helpers": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/helpers/-/helpers-7.26.0.tgz",
      "integrity": "sha512-tbhNuIxNcVb21pInl3ZSjksLCvgdZy9KwJ8brv993QtIVKJBBkYXz4q4ZbAv31GdnC+R90np23L5FbEBlthAEw==",
      "dev": true,
      "dependencies": {
        "@babel/template": "^7.25.9",
        "@babel/types": "^7.26.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/parser": {
      "version": "7.26.1",
      "resolved": "https://registry.npmmirror.com/@babel/parser/-/parser-7.26.1.tgz",
      "integrity": "sha512-reoQYNiAJreZNsJzyrDNzFQ+IQ5JFiIzAHJg9bn94S3l+4++J7RsIhNMoB+lgP/9tpmiAQqspv+xfdxTSzREOw==",
      "dev": true,
      "dependencies": {
        "@babel/types": "^7.26.0"
      },
      "bin": {
        "parser": "bin/babel-parser.js"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/standalone": {
      "version": "7.26.1",
      "resolved": "https://registry.npmmirror.com/@babel/standalone/-/standalone-7.26.1.tgz",
      "integrity": "sha512-DAC3Vv62IA9VcMMAsTm5UzuEmsVjYkR5A9BX9zJrrrPHCQYJIp38jMHHx17RC4KwruwiIAb5hLFZLmE+wZgiyQ==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/template": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/template/-/template-7.25.9.tgz",
      "integrity": "sha512-9DGttpmPvIxBb/2uwpVo3dqJ+O6RooAFOS+lB+xDqoE2PVCE8nfoHMdZLpfCQRLwvohzXISPZcgxt80xLfsuwg==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.25.9",
        "@babel/parser": "^7.25.9",
        "@babel/types": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse": {
      "version": "7.25.9",
      "resolved": "https://registry.npmmirror.com/@babel/traverse/-/traverse-7.25.9.tgz",
      "integrity": "sha512-ZCuvfwOwlz/bawvAuvcj8rrithP2/N55Tzz342AkTvq4qaWbGfmCk/tKhNaV2cthijKrPAA8SRJV5WWe7IBMJw==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.25.9",
        "@babel/generator": "^7.25.9",
        "@babel/parser": "^7.25.9",
        "@babel/template": "^7.25.9",
        "@babel/types": "^7.25.9",
        "debug": "^4.3.1",
        "globals": "^11.1.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/types": {
      "version": "7.26.0",
      "resolved": "https://registry.npmmirror.com/@babel/types/-/types-7.26.0.tgz",
      "integrity": "sha512-Z/yiTPj+lDVnF7lWeKCIJzaIkI0vYO87dMpZ4bg4TDrFe4XXLFWL1TbXU27gBP3QccxV9mZICCrnjnYlJjXHOA==",
      "dev": true,
      "dependencies": {
        "@babel/helper-string-parser": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@esbuild/aix-ppc64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/aix-ppc64/-/aix-ppc64-0.19.12.tgz",
      "integrity": "sha512-bmoCYyWdEL3wDQIVbcyzRyeKLgk2WtWLTWz1ZIAZF/EGbNOwSA6ew3PftJ1PqMiOOGu0OyFMzG53L0zqIpPeNA==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-arm/-/android-arm-0.19.12.tgz",
      "integrity": "sha512-qg/Lj1mu3CdQlDEEiWrlC4eaPZ1KztwGJ9B6J+/6G+/4ewxJg7gqj8eVYWvao1bXrqGiW2rsBZFSX3q2lcW05w==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-arm64/-/android-arm64-0.19.12.tgz",
      "integrity": "sha512-P0UVNGIienjZv3f5zq0DP3Nt2IE/3plFzuaS96vihvD0Hd6H/q4WXUGpCxD/E8YrSXfNyRPbpTq+T8ZQioSuPA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/android-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-x64/-/android-x64-0.19.12.tgz",
      "integrity": "sha512-3k7ZoUW6Q6YqhdhIaq/WZ7HwBpnFBlW905Fa4s4qWJyiNOgT1dOqDiVAQFwBH7gBRZr17gLrlFCRzF6jFh7Kew==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/darwin-arm64/-/darwin-arm64-0.19.12.tgz",
      "integrity": "sha512-B6IeSgZgtEzGC42jsI+YYu9Z3HKRxp8ZT3cqhvliEHovq8HSX2YX8lNocDn79gCKJXOSaEot9MVYky7AKjCs8g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/darwin-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/darwin-x64/-/darwin-x64-0.19.12.tgz",
      "integrity": "sha512-hKoVkKzFiToTgn+41qGhsUJXFlIjxI/jSYeZf3ugemDYZldIXIxhvwN6erJGlX4t5h417iFuheZ7l+YVn05N3A==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/freebsd-arm64/-/freebsd-arm64-0.19.12.tgz",
      "integrity": "sha512-4aRvFIXmwAcDBw9AueDQ2YnGmz5L6obe5kmPT8Vd+/+x/JMVKCgdcRwH6APrbpNXsPz+K653Qg8HB/oXvXVukA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/freebsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/freebsd-x64/-/freebsd-x64-0.19.12.tgz",
      "integrity": "sha512-EYoXZ4d8xtBoVN7CEwWY2IN4ho76xjYXqSXMNccFSx2lgqOG/1TBPW0yPx1bJZk94qu3tX0fycJeeQsKovA8gg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-arm/-/linux-arm-0.19.12.tgz",
      "integrity": "sha512-J5jPms//KhSNv+LO1S1TX1UWp1ucM6N6XuL6ITdKWElCu8wXP72l9MM0zDTzzeikVyqFE6U8YAV9/tFyj0ti+w==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-arm64/-/linux-arm64-0.19.12.tgz",
      "integrity": "sha512-EoTjyYyLuVPfdPLsGVVVC8a0p1BFFvtpQDB/YLEhaXyf/5bczaGeN15QkR+O4S5LeJ92Tqotve7i1jn35qwvdA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ia32": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-ia32/-/linux-ia32-0.19.12.tgz",
      "integrity": "sha512-Thsa42rrP1+UIGaWz47uydHSBOgTUnwBwNq59khgIwktK6x60Hivfbux9iNR0eHCHzOLjLMLfUMLCypBkZXMHA==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-loong64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-loong64/-/linux-loong64-0.19.12.tgz",
      "integrity": "sha512-LiXdXA0s3IqRRjm6rV6XaWATScKAXjI4R4LoDlvO7+yQqFdlr1Bax62sRwkVvRIrwXxvtYEHHI4dm50jAXkuAA==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-mips64el": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-mips64el/-/linux-mips64el-0.19.12.tgz",
      "integrity": "sha512-fEnAuj5VGTanfJ07ff0gOA6IPsvrVHLVb6Lyd1g2/ed67oU1eFzL0r9WL7ZzscD+/N6i3dWumGE1Un4f7Amf+w==",
      "cpu": [
        "mips64el"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-ppc64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-ppc64/-/linux-ppc64-0.19.12.tgz",
      "integrity": "sha512-nYJA2/QPimDQOh1rKWedNOe3Gfc8PabU7HT3iXWtNUbRzXS9+vgB0Fjaqr//XNbd82mCxHzik2qotuI89cfixg==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-riscv64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-riscv64/-/linux-riscv64-0.19.12.tgz",
      "integrity": "sha512-2MueBrlPQCw5dVJJpQdUYgeqIzDQgw3QtiAHUC4RBz9FXPrskyyU3VI1hw7C0BSKB9OduwSJ79FTCqtGMWqJHg==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-s390x": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-s390x/-/linux-s390x-0.19.12.tgz",
      "integrity": "sha512-+Pil1Nv3Umes4m3AZKqA2anfhJiVmNCYkPchwFJNEJN5QxmTs1uzyy4TvmDrCRNT2ApwSari7ZIgrPeUx4UZDg==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/linux-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-x64/-/linux-x64-0.19.12.tgz",
      "integrity": "sha512-B71g1QpxfwBvNrfyJdVDexenDIt1CiDN1TIXLbhOw0KhJzE78KIFGX6OJ9MrtC0oOqMWf+0xop4qEU8JrJTwCg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/netbsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/netbsd-x64/-/netbsd-x64-0.19.12.tgz",
      "integrity": "sha512-3ltjQ7n1owJgFbuC61Oj++XhtzmymoCihNFgT84UAmJnxJfm4sYCiSLTXZtE00VWYpPMYc+ZQmB6xbSdVh0JWA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/openbsd-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/openbsd-arm64/-/openbsd-arm64-0.24.0.tgz",
      "integrity": "sha512-MD9uzzkPQbYehwcN583yx3Tu5M8EIoTD+tUgKF982WYL9Pf5rKy9ltgD0eUgs8pvKnmizxjXZyLt0z6DC3rRXg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/openbsd-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/openbsd-x64/-/openbsd-x64-0.19.12.tgz",
      "integrity": "sha512-RbrfTB9SWsr0kWmb9srfF+L933uMDdu9BIzdA7os2t0TXhCRjrQyCeOt6wVxr79CKD4c+p+YhCj31HBkYcXebw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/sunos-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/sunos-x64/-/sunos-x64-0.19.12.tgz",
      "integrity": "sha512-HKjJwRrW8uWtCQnQOz9qcU3mUZhTUQvi56Q8DPTLLB+DawoiQdjsYq+j+D3s9I8VFtDr+F9CjgXKKC4ss89IeA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-arm64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-arm64/-/win32-arm64-0.19.12.tgz",
      "integrity": "sha512-URgtR1dJnmGvX864pn1B2YUYNzjmXkuJOIqG2HdU62MVS4EHpU2946OZoTMnRUHklGtJdJZ33QfzdjGACXhn1A==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-ia32": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-ia32/-/win32-ia32-0.19.12.tgz",
      "integrity": "sha512-+ZOE6pUkMOJfmxmBZElNOx72NKpIa/HFOMGzu8fqzQJ5kgf6aTGrcJaFsNiVMH4JKpMipyK+7k0n2UXN7a8YKQ==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@esbuild/win32-x64": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-x64/-/win32-x64-0.19.12.tgz",
      "integrity": "sha512-T1QyPSDCyMXaO3pzBkF96E8xMkiRYbUEZADd29SyPGabqxMViNoii+NcK7eWJAEoU6RZyEm5lVSIjTmcdoB9HA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@iarna/toml": {
      "version": "2.2.5",
      "resolved": "https://registry.npmmirror.com/@iarna/toml/-/toml-2.2.5.tgz",
      "integrity": "sha512-trnsAYxU3xnS1gPHPyU961coFyLkh4gAD/0zQ5mymY4yOZ+CYvsPqUbOFSw0aDM4y0tV7tiFxL/1XfXPNC6IPg==",
      "dev": true
    },
    "node_modules/@inquirer/figures": {
      "version": "1.0.8",
      "resolved": "https://registry.npmmirror.com/@inquirer/figures/-/figures-1.0.8.tgz",
      "integrity": "sha512-tKd+jsmhq21AP1LhexC0pPwsCxEhGgAkg28byjJAd+xhmIs8LUX8JbUc3vBf3PhLxWiB5EvyBE5X7JSPAqMAqg==",
      "dev": true,
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@isaacs/cliui": {
      "version": "8.0.2",
      "resolved": "https://registry.npmmirror.com/@isaacs/cliui/-/cliui-8.0.2.tgz",
      "integrity": "sha512-O8jcjabXaleOG9DQ0+ARXWZBTfnP4WNAqzuiJK7ll44AmxGKv/J2M4TPjxjY3znBCfvBXFzucm1twdyFybFqEA==",
      "dependencies": {
        "string-width": "^5.1.2",
        "string-width-cjs": "npm:string-width@^4.2.0",
        "strip-ansi": "^7.0.1",
        "strip-ansi-cjs": "npm:strip-ansi@^6.0.1",
        "wrap-ansi": "^8.1.0",
        "wrap-ansi-cjs": "npm:wrap-ansi@^7.0.0"
      },
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@isaacs/cliui/node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg=="
    },
    "node_modules/@isaacs/cliui/node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@jridgewell/gen-mapping": {
      "version": "0.3.5",
      "resolved": "https://registry.npmmirror.com/@jridgewell/gen-mapping/-/gen-mapping-0.3.5.tgz",
      "integrity": "sha512-IzL8ZoEDIBRWEzlCcRhOaCupYyN5gdIK+Q6fbFdPDg6HqX6jpkItn7DFIpW9LQzXG6Df9sA7+OKnq0qlz/GaQg==",
      "dev": true,
      "dependencies": {
        "@jridgewell/set-array": "^1.2.1",
        "@jridgewell/sourcemap-codec": "^1.4.10",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/resolve-uri": {
      "version": "3.1.2",
      "resolved": "https://registry.npmmirror.com/@jridgewell/resolve-uri/-/resolve-uri-3.1.2.tgz",
      "integrity": "sha512-bRISgCIjP20/tbWSPWMEi54QVPRZExkuD9lJL+UIxUKtwVJA8wW1Trb1jMs1RFXo1CBTNZ/5hpC9QvmKWdopKw==",
      "dev": true,
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/set-array": {
      "version": "1.2.1",
      "resolved": "https://registry.npmmirror.com/@jridgewell/set-array/-/set-array-1.2.1.tgz",
      "integrity": "sha512-R8gLRTZeyp03ymzP/6Lil/28tGeGEzhx1q2k703KGWRAI1VdvPIXdG70VJc2pAMw3NA6JKL5hhFu1sJX0Mnn/A==",
      "dev": true,
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/sourcemap-codec": {
      "version": "1.5.0",
      "resolved": "https://registry.npmmirror.com/@jridgewell/sourcemap-codec/-/sourcemap-codec-1.5.0.tgz",
      "integrity": "sha512-gv3ZRaISU3fjPAgNsriBRqGWQL6quFx04YMPW/zD8XMLsU32mhCCbfbO6KZFLjvYpCZ8zyDEgqsgf+PwPaM7GQ==",
      "dev": true
    },
    "node_modules/@jridgewell/trace-mapping": {
      "version": "0.3.25",
      "resolved": "https://registry.npmmirror.com/@jridgewell/trace-mapping/-/trace-mapping-0.3.25.tgz",
      "integrity": "sha512-vNk6aEwybGtawWmy/PzwnGDOjCkLWSD2wqvjGGAgOAwCGWySYXfYoxt00IJkTF+8Lb57DwOb3Aa0o9CApepiYQ==",
      "dev": true,
      "dependencies": {
        "@jridgewell/resolve-uri": "^3.1.0",
        "@jridgewell/sourcemap-codec": "^1.4.14"
      }
    },
    "node_modules/@nodelib/fs.scandir": {
      "version": "2.1.5",
      "resolved": "https://registry.npmmirror.com/@nodelib/fs.scandir/-/fs.scandir-2.1.5.tgz",
      "integrity": "sha512-vq24Bq3ym5HEQm2NKCr3yXDwjc7vTsEThRDnkp2DK9p1uqLR+DHurm/NOTo0KG7HYHU7eppKZj3MyqYuMBf62g==",
      "dev": true,
      "dependencies": {
        "@nodelib/fs.stat": "2.0.5",
        "run-parallel": "^1.1.9"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.stat": {
      "version": "2.0.5",
      "resolved": "https://registry.npmmirror.com/@nodelib/fs.stat/-/fs.stat-2.0.5.tgz",
      "integrity": "sha512-RkhPPp2zrqDAQA/2jNhnztcPAlv64XdhIp7a7454A5ovI7Bukxgt7MX7udwAu3zg1DcpPU0rz3VV1SeaqvY4+A==",
      "dev": true,
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.walk": {
      "version": "1.2.8",
      "resolved": "https://registry.npmmirror.com/@nodelib/fs.walk/-/fs.walk-1.2.8.tgz",
      "integrity": "sha512-oGB+UxlgWcgQkgwo8GcEGwemoTFt3FIO9ababBmaGwXIoBKZ+GTy0pP185beGg7Llih/NSHSV2XAs1lnznocSg==",
      "dev": true,
      "dependencies": {
        "@nodelib/fs.scandir": "2.1.5",
        "fastq": "^1.6.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@octokit/auth-token": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/@octokit/auth-token/-/auth-token-4.0.0.tgz",
      "integrity": "sha512-tY/msAuJo6ARbK6SPIxZrPBms3xPbfwBrulZe0Wtr/DIY9lje2HeV1uoebShn6mx7SjCHif6EjMvoREj+gZ+SA==",
      "dev": true,
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/core": {
      "version": "5.2.0",
      "resolved": "https://registry.npmmirror.com/@octokit/core/-/core-5.2.0.tgz",
      "integrity": "sha512-1LFfa/qnMQvEOAdzlQymH0ulepxbxnCYAKJZfMci/5XJyIHWgEYnDmgnKakbTh7CH2tFQ5O60oYDvns4i9RAIg==",
      "dev": true,
      "dependencies": {
        "@octokit/auth-token": "^4.0.0",
        "@octokit/graphql": "^7.1.0",
        "@octokit/request": "^8.3.1",
        "@octokit/request-error": "^5.1.0",
        "@octokit/types": "^13.0.0",
        "before-after-hook": "^2.2.0",
        "universal-user-agent": "^6.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/endpoint": {
      "version": "9.0.5",
      "resolved": "https://registry.npmmirror.com/@octokit/endpoint/-/endpoint-9.0.5.tgz",
      "integrity": "sha512-ekqR4/+PCLkEBF6qgj8WqJfvDq65RH85OAgrtnVp1mSxaXF03u2xW/hUdweGS5654IlC0wkNYC18Z50tSYTAFw==",
      "dev": true,
      "dependencies": {
        "@octokit/types": "^13.1.0",
        "universal-user-agent": "^6.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/graphql": {
      "version": "7.1.0",
      "resolved": "https://registry.npmmirror.com/@octokit/graphql/-/graphql-7.1.0.tgz",
      "integrity": "sha512-r+oZUH7aMFui1ypZnAvZmn0KSqAUgE1/tUXIWaqUCa1758ts/Jio84GZuzsvUkme98kv0WFY8//n0J1Z+vsIsQ==",
      "dev": true,
      "dependencies": {
        "@octokit/request": "^8.3.0",
        "@octokit/types": "^13.0.0",
        "universal-user-agent": "^6.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/openapi-types": {
      "version": "22.2.0",
      "resolved": "https://registry.npmmirror.com/@octokit/openapi-types/-/openapi-types-22.2.0.tgz",
      "integrity": "sha512-QBhVjcUa9W7Wwhm6DBFu6ZZ+1/t/oYxqc2tp81Pi41YNuJinbFRx8B133qVOrAaBbF7D/m0Et6f9/pZt9Rc+tg==",
      "dev": true
    },
    "node_modules/@octokit/plugin-paginate-rest": {
      "version": "11.3.1",
      "resolved": "https://registry.npmmirror.com/@octokit/plugin-paginate-rest/-/plugin-paginate-rest-11.3.1.tgz",
      "integrity": "sha512-ryqobs26cLtM1kQxqeZui4v8FeznirUsksiA+RYemMPJ7Micju0WSkv50dBksTuZks9O5cg4wp+t8fZ/cLY56g==",
      "dev": true,
      "dependencies": {
        "@octokit/types": "^13.5.0"
      },
      "engines": {
        "node": ">= 18"
      },
      "peerDependencies": {
        "@octokit/core": "5"
      }
    },
    "node_modules/@octokit/plugin-request-log": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/@octokit/plugin-request-log/-/plugin-request-log-4.0.1.tgz",
      "integrity": "sha512-GihNqNpGHorUrO7Qa9JbAl0dbLnqJVrV8OXe2Zm5/Y4wFkZQDfTreBzVmiRfJVfE4mClXdihHnbpyyO9FSX4HA==",
      "dev": true,
      "engines": {
        "node": ">= 18"
      },
      "peerDependencies": {
        "@octokit/core": "5"
      }
    },
    "node_modules/@octokit/plugin-rest-endpoint-methods": {
      "version": "13.2.2",
      "resolved": "https://registry.npmmirror.com/@octokit/plugin-rest-endpoint-methods/-/plugin-rest-endpoint-methods-13.2.2.tgz",
      "integrity": "sha512-EI7kXWidkt3Xlok5uN43suK99VWqc8OaIMktY9d9+RNKl69juoTyxmLoWPIZgJYzi41qj/9zU7G/ljnNOJ5AFA==",
      "dev": true,
      "dependencies": {
        "@octokit/types": "^13.5.0"
      },
      "engines": {
        "node": ">= 18"
      },
      "peerDependencies": {
        "@octokit/core": "^5"
      }
    },
    "node_modules/@octokit/request": {
      "version": "8.4.0",
      "resolved": "https://registry.npmmirror.com/@octokit/request/-/request-8.4.0.tgz",
      "integrity": "sha512-9Bb014e+m2TgBeEJGEbdplMVWwPmL1FPtggHQRkV+WVsMggPtEkLKPlcVYm/o8xKLkpJ7B+6N8WfQMtDLX2Dpw==",
      "dev": true,
      "dependencies": {
        "@octokit/endpoint": "^9.0.1",
        "@octokit/request-error": "^5.1.0",
        "@octokit/types": "^13.1.0",
        "universal-user-agent": "^6.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/request-error": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/@octokit/request-error/-/request-error-5.1.0.tgz",
      "integrity": "sha512-GETXfE05J0+7H2STzekpKObFe765O5dlAKUTLNGeH+x47z7JjXHfsHKo5z21D/o/IOZTUEI6nyWyR+bZVP/n5Q==",
      "dev": true,
      "dependencies": {
        "@octokit/types": "^13.1.0",
        "deprecation": "^2.0.0",
        "once": "^1.4.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/rest": {
      "version": "20.1.1",
      "resolved": "https://registry.npmmirror.com/@octokit/rest/-/rest-20.1.1.tgz",
      "integrity": "sha512-MB4AYDsM5jhIHro/dq4ix1iWTLGToIGk6cWF5L6vanFaMble5jTX/UBQyiv05HsWnwUtY8JrfHy2LWfKwihqMw==",
      "dev": true,
      "dependencies": {
        "@octokit/core": "^5.0.2",
        "@octokit/plugin-paginate-rest": "11.3.1",
        "@octokit/plugin-request-log": "^4.0.0",
        "@octokit/plugin-rest-endpoint-methods": "13.2.2"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/@octokit/types": {
      "version": "13.6.2",
      "resolved": "https://registry.npmmirror.com/@octokit/types/-/types-13.6.2.tgz",
      "integrity": "sha512-WpbZfZUcZU77DrSW4wbsSgTPfKcp286q3ItaIgvSbBpZJlu6mnYXAkjZz6LVZPXkEvLIM8McanyZejKTYUHipA==",
      "dev": true,
      "dependencies": {
        "@octokit/openapi-types": "^22.2.0"
      }
    },
    "node_modules/@pnpm/config.env-replace": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/@pnpm/config.env-replace/-/config.env-replace-1.1.0.tgz",
      "integrity": "sha512-htyl8TWnKL7K/ESFa1oW2UB5lVDxuF5DpM7tBi6Hu2LNL3mWkIzNLG6N4zoCUP1lCKNxWy/3iu8mS8MvToGd6w==",
      "dev": true,
      "engines": {
        "node": ">=12.22.0"
      }
    },
    "node_modules/@pnpm/network.ca-file": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/@pnpm/network.ca-file/-/network.ca-file-1.0.2.tgz",
      "integrity": "sha512-YcPQ8a0jwYU9bTdJDpXjMi7Brhkr1mXsXrUJvjqM2mQDgkRiz8jFaQGOdaLxgjtUfQgZhKy/O3cG/YwmgKaxLA==",
      "dev": true,
      "dependencies": {
        "graceful-fs": "4.2.10"
      },
      "engines": {
        "node": ">=12.22.0"
      }
    },
    "node_modules/@pnpm/network.ca-file/node_modules/graceful-fs": {
      "version": "4.2.10",
      "resolved": "https://registry.npmmirror.com/graceful-fs/-/graceful-fs-4.2.10.tgz",
      "integrity": "sha512-9ByhssR2fPVsNZj478qUUbKfmL0+t5BDVyjShtyZZLiK7ZDAArFFfopyOTj0M05wE2tJPisA4iTnnXl2YoPvOA==",
      "dev": true
    },
    "node_modules/@pnpm/npm-conf": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/@pnpm/npm-conf/-/npm-conf-2.3.1.tgz",
      "integrity": "sha512-c83qWb22rNRuB0UaVCI0uRPNRr8Z0FWnEIvT47jiHAmOIUHbBOg5XvV7pM5x+rKn9HRpjxquDbXYSXr3fAKFcw==",
      "dev": true,
      "dependencies": {
        "@pnpm/config.env-replace": "^1.1.0",
        "@pnpm/network.ca-file": "^1.0.1",
        "config-chain": "^1.1.11"
      },
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@rollup/plugin-alias": {
      "version": "5.1.1",
      "resolved": "https://registry.npmmirror.com/@rollup/plugin-alias/-/plugin-alias-5.1.1.tgz",
      "integrity": "sha512-PR9zDb+rOzkRb2VD+EuKB7UC41vU5DIwZ5qqCpk0KJudcWAyi8rvYOhS7+L5aZCspw1stTViLgN5v6FF1p5cgQ==",
      "dev": true,
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^1.20.0||^2.0.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/plugin-commonjs": {
      "version": "25.0.8",
      "resolved": "https://registry.npmmirror.com/@rollup/plugin-commonjs/-/plugin-commonjs-25.0.8.tgz",
      "integrity": "sha512-ZEZWTK5n6Qde0to4vS9Mr5x/0UZoqCxPVR9KRUjU4kA2sO7GEUn1fop0DAwpO6z0Nw/kJON9bDmSxdWxO/TT1A==",
      "dev": true,
      "dependencies": {
        "@rollup/pluginutils": "^5.0.1",
        "commondir": "^1.0.1",
        "estree-walker": "^2.0.2",
        "glob": "^8.0.3",
        "is-reference": "1.2.1",
        "magic-string": "^0.30.3"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^2.68.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/plugin-json": {
      "version": "6.1.0",
      "resolved": "https://registry.npmmirror.com/@rollup/plugin-json/-/plugin-json-6.1.0.tgz",
      "integrity": "sha512-EGI2te5ENk1coGeADSIwZ7G2Q8CJS2sF120T7jLw4xFw9n7wIOXHo+kIYRAoVpJAN+kmqZSoO3Fp4JtoNF4ReA==",
      "dev": true,
      "dependencies": {
        "@rollup/pluginutils": "^5.1.0"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^1.20.0||^2.0.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/plugin-node-resolve": {
      "version": "15.3.0",
      "resolved": "https://registry.npmmirror.com/@rollup/plugin-node-resolve/-/plugin-node-resolve-15.3.0.tgz",
      "integrity": "sha512-9eO5McEICxMzJpDW9OnMYSv4Sta3hmt7VtBFz5zR9273suNOydOyq/FrGeGy+KsTRFm8w0SLVhzig2ILFT63Ag==",
      "dev": true,
      "dependencies": {
        "@rollup/pluginutils": "^5.0.1",
        "@types/resolve": "1.20.2",
        "deepmerge": "^4.2.2",
        "is-module": "^1.0.0",
        "resolve": "^1.22.1"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^2.78.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/plugin-replace": {
      "version": "5.0.7",
      "resolved": "https://registry.npmmirror.com/@rollup/plugin-replace/-/plugin-replace-5.0.7.tgz",
      "integrity": "sha512-PqxSfuorkHz/SPpyngLyg5GCEkOcee9M1bkxiVDr41Pd61mqP1PLOoDPbpl44SB2mQGKwV/In74gqQmGITOhEQ==",
      "dev": true,
      "dependencies": {
        "@rollup/pluginutils": "^5.0.1",
        "magic-string": "^0.30.3"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^1.20.0||^2.0.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/pluginutils": {
      "version": "5.1.3",
      "resolved": "https://registry.npmmirror.com/@rollup/pluginutils/-/pluginutils-5.1.3.tgz",
      "integrity": "sha512-Pnsb6f32CD2W3uCaLZIzDmeFyQ2b8UWMFI7xtwUezpcGBDVDW6y9XgAWIlARiGAo6eNF5FK5aQTr0LFyNyqq5A==",
      "dev": true,
      "dependencies": {
        "@types/estree": "^1.0.0",
        "estree-walker": "^2.0.2",
        "picomatch": "^4.0.2"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "rollup": "^1.20.0||^2.0.0||^3.0.0||^4.0.0"
      },
      "peerDependenciesMeta": {
        "rollup": {
          "optional": true
        }
      }
    },
    "node_modules/@sindresorhus/is": {
      "version": "0.7.0",
      "resolved": "https://registry.npmmirror.com/@sindresorhus/is/-/is-0.7.0.tgz",
      "integrity": "sha512-ONhaKPIufzzrlNbqtWFFd+jlnemX6lJAgq9ZeiZtS7I1PIf/la7CW4m83rTXRnVnsMbW2k56pGYu7AUFJD9Pow==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/@sindresorhus/merge-streams": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/@sindresorhus/merge-streams/-/merge-streams-2.3.0.tgz",
      "integrity": "sha512-LtoMMhxAlorcGhmFYI+LhPgbPZCkgP6ra1YL604EeF6U98pLlQ3iWIGMdWSC+vWmPBWBNgmDBAhnAobLROJmwg==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@tootallnate/quickjs-emscripten": {
      "version": "0.23.0",
      "resolved": "https://registry.npmmirror.com/@tootallnate/quickjs-emscripten/-/quickjs-emscripten-0.23.0.tgz",
      "integrity": "sha512-C5Mc6rdnsaJDjO3UpGW/CQTHtCKaYlScZTly4JIu97Jxo/odCiH0ITnDXSJPTOrEKk/ycSZ0AOgTmkDtkOsvIA==",
      "dev": true
    },
    "node_modules/@trysound/sax": {
      "version": "0.2.0",
      "resolved": "https://registry.npmmirror.com/@trysound/sax/-/sax-0.2.0.tgz",
      "integrity": "sha512-L7z9BgrNEcYyUYtF+HaEfiS5ebkh9jXqbszz7pC0hRBPaatV0XjSD3+eHrpqFemQfgwiFF0QPIarnIihIDn7OA==",
      "dev": true,
      "engines": {
        "node": ">=10.13.0"
      }
    },
    "node_modules/@types/estree": {
      "version": "1.0.6",
      "resolved": "https://registry.npmmirror.com/@types/estree/-/estree-1.0.6.tgz",
      "integrity": "sha512-AYnb1nQyY49te+VRAVgmzfcgjYS91mY5P0TKUDCLEM+gNnA+3T6rWITXRLYCpahpqSQbN5cE+gHpnPyXjHWxcw==",
      "dev": true
    },
    "node_modules/@types/resolve": {
      "version": "1.20.2",
      "resolved": "https://registry.npmmirror.com/@types/resolve/-/resolve-1.20.2.tgz",
      "integrity": "sha512-60BCwRFOZCQhDncwQdxxeOEEkbc5dIMccYLwbxsS4TUNeVECQ/pBJ0j09mrHOl/JJvpRPGwO9SvE4nR2Nb/a4Q==",
      "dev": true
    },
    "node_modules/acorn": {
      "version": "8.14.0",
      "resolved": "https://registry.npmmirror.com/acorn/-/acorn-8.14.0.tgz",
      "integrity": "sha512-cl669nCJTZBsL97OF4kUQm5g5hC2uihk0NxY3WENAC0TYdILVkAyHymAntgxGkl7K+t0cXIrH5siy5S4XkFycA==",
      "dev": true,
      "bin": {
        "acorn": "bin/acorn"
      },
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/agent-base": {
      "version": "7.1.1",
      "resolved": "https://registry.npmmirror.com/agent-base/-/agent-base-7.1.1.tgz",
      "integrity": "sha512-H0TSyFNDMomMNJQBn8wFV5YC/2eJ+VXECwOadZJT554xP6cODZHPX3H9QMQECxvrgiSOP1pHjy1sMWQVYJOUOA==",
      "dev": true,
      "dependencies": {
        "debug": "^4.3.4"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/ansi-align": {
      "version": "3.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-align/-/ansi-align-3.0.1.tgz",
      "integrity": "sha512-IOfwwBF5iczOjp/WeY4YxyjqAFMQoZufdQWDd19SEExbVLNXqvpzSJ/M7Za4/sCPmQ0+GRquoA7bGcINcxew6w==",
      "dev": true,
      "dependencies": {
        "string-width": "^4.1.0"
      }
    },
    "node_modules/ansi-align/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ansi-align/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true
    },
    "node_modules/ansi-align/node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ansi-align/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/ansi-escapes": {
      "version": "4.3.2",
      "resolved": "https://registry.npmmirror.com/ansi-escapes/-/ansi-escapes-4.3.2.tgz",
      "integrity": "sha512-gKXj5ALrKWQLsYG9jlTRmR/xKluxHV+Z9QEwNIgCfM1/uwPMCuzVVnh5mwTd+OuBZcwSIMbqssNWRm1lE51QaQ==",
      "dev": true,
      "dependencies": {
        "type-fest": "^0.21.3"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/ansi-regex": {
      "version": "6.1.0",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-6.1.0.tgz",
      "integrity": "sha512-7HSX4QQb4CspciLpVFwyRe79O3xsIZDDLER21kERQ71oaPodF8jL725AgJMFAYbooIqolJoRLuM81SpeUkpkvA==",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-regex?sponsor=1"
      }
    },
    "node_modules/ansi-styles": {
      "version": "6.2.1",
      "resolved": "https://registry.npmmirror.com/ansi-styles/-/ansi-styles-6.2.1.tgz",
      "integrity": "sha512-bN798gFfQX+viw3R7yrGWRqnrN2oRkEkUjjl4JNn4E8GxxbjtG3FbrEIIY3l8/hrwUwIeCZvi4QuOTP4MErVug==",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/archive-type": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/archive-type/-/archive-type-4.0.0.tgz",
      "integrity": "sha512-zV4Ky0v1F8dBrdYElwTvQhweQ0P7Kwc1aluqJsYtOBP01jXcWCyW2IEfI1YiqsG+Iy7ZR+o5LF1N+PGECBxHWA==",
      "dependencies": {
        "file-type": "^4.2.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/archive-type/node_modules/file-type": {
      "version": "4.4.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-4.4.0.tgz",
      "integrity": "sha512-f2UbFQEk7LXgWpi5ntcO86OeA/cC80fuDDDaX/fZ2ZGel+AF7leRQqBBW1eJNiiQkrZlAoM6P+VYP5P6bOlDEQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/argparse": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/argparse/-/argparse-2.0.1.tgz",
      "integrity": "sha512-8+9WqebbFzpX9OR+Wa6O29asIogeRMzcGtAINdpMHHyAg10f05aSFVBbcEqGf/PXw1EjAZ+q2/bEBg3DvurK3Q==",
      "dev": true
    },
    "node_modules/ast-types": {
      "version": "0.13.4",
      "resolved": "https://registry.npmmirror.com/ast-types/-/ast-types-0.13.4.tgz",
      "integrity": "sha512-x1FCFnFifvYDDzTaLII71vG5uvDwgtmDTEVWAxrgeiR8VjMONcCXJx7E+USjDtHlwFmt9MysbqgF9b9Vjr6w+w==",
      "dev": true,
      "dependencies": {
        "tslib": "^2.0.1"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/async-retry": {
      "version": "1.3.3",
      "resolved": "https://registry.npmmirror.com/async-retry/-/async-retry-1.3.3.tgz",
      "integrity": "sha512-wfr/jstw9xNi/0teMHrRW7dsz3Lt5ARhYNZ2ewpadnhaIp5mbALhOAP+EAdsC7t4Z6wqsDVv9+W6gm1Dk9mEyw==",
      "dev": true,
      "dependencies": {
        "retry": "0.13.1"
      }
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmmirror.com/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q=="
    },
    "node_modules/atomically": {
      "version": "2.0.3",
      "resolved": "https://registry.npmmirror.com/atomically/-/atomically-2.0.3.tgz",
      "integrity": "sha512-kU6FmrwZ3Lx7/7y3hPS5QnbJfaohcIul5fGqf7ok+4KklIEk9tJ0C2IQPdacSbVUWv6zVHXEBWoWd6NrVMT7Cw==",
      "dev": true,
      "dependencies": {
        "stubborn-fs": "^1.2.5",
        "when-exit": "^2.1.1"
      }
    },
    "node_modules/autoprefixer": {
      "version": "10.4.20",
      "resolved": "https://registry.npmmirror.com/autoprefixer/-/autoprefixer-10.4.20.tgz",
      "integrity": "sha512-XY25y5xSv/wEoqzDyXXME4AFfkZI0P23z6Fs3YgymDnKJkCGOnkL0iTxCa85UTqaSgfcqyf3UA6+c7wUvx/16g==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/autoprefixer"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "dependencies": {
        "browserslist": "^4.23.3",
        "caniuse-lite": "^1.0.30001646",
        "fraction.js": "^4.3.7",
        "normalize-range": "^0.1.2",
        "picocolors": "^1.0.1",
        "postcss-value-parser": "^4.2.0"
      },
      "bin": {
        "autoprefixer": "bin/autoprefixer"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      },
      "peerDependencies": {
        "postcss": "^8.1.0"
      }
    },
    "node_modules/axios": {
      "version": "1.7.7",
      "resolved": "https://registry.npmmirror.com/axios/-/axios-1.7.7.tgz",
      "integrity": "sha512-S4kL7XrjgBmvdGut0sN3yJxqYzrDOnivkBiN0OFs6hLiUam3UPvswUo0kqGyhqUZGEOytHyumEdXsAkgCOUf3Q==",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw=="
    },
    "node_modules/base64-js": {
      "version": "1.5.1",
      "resolved": "https://registry.npmmirror.com/base64-js/-/base64-js-1.5.1.tgz",
      "integrity": "sha512-AKpaYlHn8t4SVbOHCy+b5+KKgvR4vrsD8vbvrbiQJps7fKDTkjkDry6ji0rUJjC0kzbNePLwzxq8iypo41qeWA==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ]
    },
    "node_modules/basic-ftp": {
      "version": "5.0.5",
      "resolved": "https://registry.npmmirror.com/basic-ftp/-/basic-ftp-5.0.5.tgz",
      "integrity": "sha512-4Bcg1P8xhUuqcii/S0Z9wiHIrQVPMermM1any+MX5GeGD7faD3/msQUDGLol9wOcz4/jbg/WJnGqoJF6LiBdtg==",
      "dev": true,
      "engines": {
        "node": ">=10.0.0"
      }
    },
    "node_modules/before-after-hook": {
      "version": "2.2.3",
      "resolved": "https://registry.npmmirror.com/before-after-hook/-/before-after-hook-2.2.3.tgz",
      "integrity": "sha512-NzUnlZexiaH/46WDhANlyR2bXRopNg4F/zuSA3OpZnllCUgRaOF2znDioDWrmbNVsuZk6l9pMquQB38cfBZwkQ==",
      "dev": true
    },
    "node_modules/bl": {
      "version": "1.2.3",
      "resolved": "https://registry.npmmirror.com/bl/-/bl-1.2.3.tgz",
      "integrity": "sha512-pvcNpa0UU69UT341rO6AYy4FVAIkUHuZXRIWbq+zHnsVcRzDDjIAhGuuYoi0d//cwIwtt4pkpKycWEfjdV+vww==",
      "dependencies": {
        "readable-stream": "^2.3.5",
        "safe-buffer": "^5.1.1"
      }
    },
    "node_modules/boolbase": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/boolbase/-/boolbase-1.0.0.tgz",
      "integrity": "sha512-JZOSA7Mo9sNGB8+UjSgzdLtokWAky1zbztM3WRLCbZ70/3cTANmQmOdR7y2g+J0e2WXywy1yS468tY+IruqEww==",
      "dev": true
    },
    "node_modules/boxen": {
      "version": "8.0.1",
      "resolved": "https://registry.npmmirror.com/boxen/-/boxen-8.0.1.tgz",
      "integrity": "sha512-F3PH5k5juxom4xktynS7MoFY+NUWH5LC4CnH11YB8NPew+HLpmBLCybSAEyb2F+4pRXhuhWqFesoQd6DAyc2hw==",
      "dev": true,
      "dependencies": {
        "ansi-align": "^3.0.1",
        "camelcase": "^8.0.0",
        "chalk": "^5.3.0",
        "cli-boxes": "^3.0.0",
        "string-width": "^7.2.0",
        "type-fest": "^4.21.0",
        "widest-line": "^5.0.0",
        "wrap-ansi": "^9.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/type-fest": {
      "version": "4.28.1",
      "resolved": "https://registry.npmmirror.com/type-fest/-/type-fest-4.28.1.tgz",
      "integrity": "sha512-LO/+yb3mf46YqfUC7QkkoAlpa7CTYh//V1Xy9+NQ+pKqDqXIq0NTfPfQRwFfCt+if4Qkwb9gzZfsl6E5TkXZGw==",
      "dev": true,
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/boxen/node_modules/wrap-ansi": {
      "version": "9.0.0",
      "resolved": "https://registry.npmmirror.com/wrap-ansi/-/wrap-ansi-9.0.0.tgz",
      "integrity": "sha512-G8ura3S+3Z2G+mkgNRq8dqaFZAuxfsxpBB8OCTGRTCtp+l/v9nbFNmCUP1BZMts3G1142MsZfn6eeUKrr4PD1Q==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^6.2.1",
        "string-width": "^7.0.0",
        "strip-ansi": "^7.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/brace-expansion": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/brace-expansion/-/brace-expansion-2.0.1.tgz",
      "integrity": "sha512-XnAIvQ8eM+kC6aULx6wuQiwVsnzsi9d3WxzV3FpWTGA19F621kwdbsAcFKXgKUHZWsy+mY6iL1sHTxWEFCytDA==",
      "dependencies": {
        "balanced-match": "^1.0.0"
      }
    },
    "node_modules/braces": {
      "version": "3.0.3",
      "resolved": "https://registry.npmmirror.com/braces/-/braces-3.0.3.tgz",
      "integrity": "sha512-yQbXgO/OSZVD2IsiLlro+7Hf6Q18EJrKSEsdoMzKePKXct3gvD8oLcOQdIzGupr5Fj+EDe8gO/lxc1BzfMpxvA==",
      "dev": true,
      "dependencies": {
        "fill-range": "^7.1.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/browserslist": {
      "version": "4.24.2",
      "resolved": "https://registry.npmmirror.com/browserslist/-/browserslist-4.24.2.tgz",
      "integrity": "sha512-ZIc+Q62revdMcqC6aChtW4jz3My3klmCO1fEmINZY/8J3EpBg5/A/D0AKmBveUh6pgoeycoMkVMko84tuYS+Gg==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "dependencies": {
        "caniuse-lite": "^1.0.30001669",
        "electron-to-chromium": "^1.5.41",
        "node-releases": "^2.0.18",
        "update-browserslist-db": "^1.1.1"
      },
      "bin": {
        "browserslist": "cli.js"
      },
      "engines": {
        "node": "^6 || ^7 || ^8 || ^9 || ^10 || ^11 || ^12 || >=13.7"
      }
    },
    "node_modules/buffer": {
      "version": "5.7.1",
      "resolved": "https://registry.npmmirror.com/buffer/-/buffer-5.7.1.tgz",
      "integrity": "sha512-EHcyIPBQ4BSGlvjB16k5KgAJ27CIsHY/2JBmCRReo48y9rQ3MaUzWX3KVlBa4U7MyX02HdVj0K7C3WaB3ju7FQ==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "dependencies": {
        "base64-js": "^1.3.1",
        "ieee754": "^1.1.13"
      }
    },
    "node_modules/buffer-alloc": {
      "version": "1.2.0",
      "resolved": "https://registry.npmmirror.com/buffer-alloc/-/buffer-alloc-1.2.0.tgz",
      "integrity": "sha512-CFsHQgjtW1UChdXgbyJGtnm+O/uLQeZdtbDo8mfUgYXCHSM1wgrVxXm6bSyrUuErEb+4sYVGCzASBRot7zyrow==",
      "dependencies": {
        "buffer-alloc-unsafe": "^1.1.0",
        "buffer-fill": "^1.0.0"
      }
    },
    "node_modules/buffer-alloc-unsafe": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/buffer-alloc-unsafe/-/buffer-alloc-unsafe-1.1.0.tgz",
      "integrity": "sha512-TEM2iMIEQdJ2yjPJoSIsldnleVaAk1oW3DBVUykyOLsEsFmEc9kn+SFFPz+gl54KQNxlDnAwCXosOS9Okx2xAg=="
    },
    "node_modules/buffer-crc32": {
      "version": "0.2.13",
      "resolved": "https://registry.npmmirror.com/buffer-crc32/-/buffer-crc32-0.2.13.tgz",
      "integrity": "sha512-VO9Ht/+p3SN7SKWqcrgEzjGbRSJYTx+Q1pTQC0wrWqHx0vpJraQ6GtHx8tvcg1rlK1byhU5gccxgOgj7B0TDkQ==",
      "engines": {
        "node": "*"
      }
    },
    "node_modules/buffer-fill": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/buffer-fill/-/buffer-fill-1.0.0.tgz",
      "integrity": "sha512-T7zexNBwiiaCOGDg9xNX9PBmjrubblRkENuptryuI64URkXDFum9il/JGL8Lm8wYfAXpredVXXZz7eMHilimiQ=="
    },
    "node_modules/bundle-name": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/bundle-name/-/bundle-name-4.1.0.tgz",
      "integrity": "sha512-tjwM5exMg6BGRI+kNmTntNsvdZS1X8BFYS6tnJ2hdH0kVxM6/eVZ2xy+FqStSWvYmtfFMDLIxurorHwDKfDz5Q==",
      "dev": true,
      "dependencies": {
        "run-applescript": "^7.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/cacheable-request": {
      "version": "2.1.4",
      "resolved": "https://registry.npmmirror.com/cacheable-request/-/cacheable-request-2.1.4.tgz",
      "integrity": "sha512-vag0O2LKZ/najSoUwDbVlnlCFvhBE/7mGTY2B5FgCBDcRD+oVV1HYTOwM6JZfMg/hIcM6IwnTZ1uQQL5/X3xIQ==",
      "dependencies": {
        "clone-response": "1.0.2",
        "get-stream": "3.0.0",
        "http-cache-semantics": "3.8.1",
        "keyv": "3.0.0",
        "lowercase-keys": "1.0.0",
        "normalize-url": "2.0.1",
        "responselike": "1.0.2"
      }
    },
    "node_modules/cacheable-request/node_modules/lowercase-keys": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/lowercase-keys/-/lowercase-keys-1.0.0.tgz",
      "integrity": "sha512-RPlX0+PHuvxVDZ7xX+EBVAp4RsVxP/TdDSN2mJYdiq1Lc4Hz7EUSjUI7RZrKKlmrIzVhf6Jo2stj7++gVarS0A==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/callsites": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/callsites/-/callsites-3.1.0.tgz",
      "integrity": "sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/camelcase": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/camelcase/-/camelcase-8.0.0.tgz",
      "integrity": "sha512-8WB3Jcas3swSvjIeA2yvCJ+Miyz5l1ZmB6HFb9R1317dt9LCQoswg/BGrmAmkWVEszSrrg4RwmO46qIm2OEnSA==",
      "dev": true,
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/caniuse-api": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/caniuse-api/-/caniuse-api-3.0.0.tgz",
      "integrity": "sha512-bsTwuIg/BZZK/vreVTYYbSWoe2F+71P7K5QGEX+pT250DZbfU1MQ5prOKpPR+LL6uWKK3KMwMCAS74QB3Um1uw==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.0.0",
        "caniuse-lite": "^1.0.0",
        "lodash.memoize": "^4.1.2",
        "lodash.uniq": "^4.5.0"
      }
    },
    "node_modules/caniuse-lite": {
      "version": "1.0.30001673",
      "resolved": "https://registry.npmmirror.com/caniuse-lite/-/caniuse-lite-1.0.30001673.tgz",
      "integrity": "sha512-WTrjUCSMp3LYX0nE12ECkV0a+e6LC85E0Auz75555/qr78Oc8YWhEPNfDd6SHdtlCMSzqtuXY0uyEMNRcsKpKw==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/caniuse-lite"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ]
    },
    "node_modules/caw": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/caw/-/caw-2.0.1.tgz",
      "integrity": "sha512-Cg8/ZSBEa8ZVY9HspcGUYaK63d/bN7rqS3CYCzEGUxuYv6UlmcjzDUz2fCFFHyTvUW5Pk0I+3hkA3iXlIj6guA==",
      "dependencies": {
        "get-proxy": "^2.0.0",
        "isurl": "^1.0.0-alpha5",
        "tunnel-agent": "^0.6.0",
        "url-to-options": "^1.0.1"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/chalk": {
      "version": "5.3.0",
      "resolved": "https://registry.npmmirror.com/chalk/-/chalk-5.3.0.tgz",
      "integrity": "sha512-dLitG79d+GV1Nb/VYcCDFivJeK1hiukt9QjRNVOsUtTy1rR1YJsmpGGTZ3qJos+uw7WmWF4wUwBd9jxjocFC2w==",
      "engines": {
        "node": "^12.17.0 || ^14.13 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/chardet": {
      "version": "0.7.0",
      "resolved": "https://registry.npmmirror.com/chardet/-/chardet-0.7.0.tgz",
      "integrity": "sha512-mT8iDcrh03qDGRRmoA2hmBJnxpllMR+0/0qlzjqZES6NdiWDcZkCNAk4rPFZ9Q85r27unkiNNg8ZOiwZXBHwcA==",
      "dev": true
    },
    "node_modules/ci-info": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/ci-info/-/ci-info-4.1.0.tgz",
      "integrity": "sha512-HutrvTNsF48wnxkzERIXOe5/mlcfFcbfCmwcg6CJnizbSue78AbDt+1cgl26zwn61WFxhcPykPfZrbqjGmBb4A==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/sibiraj-s"
        }
      ],
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/citty": {
      "version": "0.1.6",
      "resolved": "https://registry.npmmirror.com/citty/-/citty-0.1.6.tgz",
      "integrity": "sha512-tskPPKEs8D2KPafUypv2gxwJP8h/OaJmC82QQGGDQcHvXX43xF2VDACcJVmZ0EuSxkpO9Kc4MlrA3q0+FG58AQ==",
      "dev": true,
      "dependencies": {
        "consola": "^3.2.3"
      }
    },
    "node_modules/cli-boxes": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/cli-boxes/-/cli-boxes-3.0.0.tgz",
      "integrity": "sha512-/lzGpEWL/8PfI0BmBOPRwp0c/wFNX1RdUML3jK/RcSBA9T8mZDdQpqYBKtCFTOfQbwPqWEOpjqW+Fnayc0969g==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/cli-cursor": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/cli-cursor/-/cli-cursor-5.0.0.tgz",
      "integrity": "sha512-aCj4O5wKyszjMmDT4tZj93kxyydN/K5zPWSCe6/0AV/AA1pqe5ZBIw0a2ZfPQV7lL5/yb5HsUreJ6UFAF1tEQw==",
      "dependencies": {
        "restore-cursor": "^5.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/cli-spinners": {
      "version": "2.9.2",
      "resolved": "https://registry.npmmirror.com/cli-spinners/-/cli-spinners-2.9.2.tgz",
      "integrity": "sha512-ywqV+5MmyL4E7ybXgKys4DugZbX0FC6LnwrhjuykIjnK9k8OQacQ7axGKnjDXWNhns0xot3bZI5h55H8yo9cJg==",
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/cli-width": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/cli-width/-/cli-width-4.1.0.tgz",
      "integrity": "sha512-ouuZd4/dm2Sw5Gmqy6bGyNNNe1qt9RpmxveLSO7KcgsTnU7RXfsw+/bukWGo1abgBiMAic068rclZsO4IWmmxQ==",
      "dev": true,
      "engines": {
        "node": ">= 12"
      }
    },
    "node_modules/clone": {
      "version": "1.0.4",
      "resolved": "https://registry.npmmirror.com/clone/-/clone-1.0.4.tgz",
      "integrity": "sha512-JQHZ2QMW6l3aH/j6xCqQThY/9OH4D/9ls34cgkUBiEeocRTU04tHfKPBsUK1PqZCUQM7GiA0IIXJSuXHI64Kbg==",
      "dev": true,
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/clone-response": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/clone-response/-/clone-response-1.0.2.tgz",
      "integrity": "sha512-yjLXh88P599UOyPTFX0POsd7WxnbsVsGohcwzHOLspIhhpalPw1BcqED8NblyZLKcGrL8dTgMlcaZxV2jAD41Q==",
      "dependencies": {
        "mimic-response": "^1.0.0"
      }
    },
    "node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmmirror.com/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA=="
    },
    "node_modules/colord": {
      "version": "2.9.3",
      "resolved": "https://registry.npmmirror.com/colord/-/colord-2.9.3.tgz",
      "integrity": "sha512-jeC1axXpnb0/2nn/Y1LPuLdgXBLH7aDcHu4KEKfqw3CUhX7ZpfBSlPKyqXE6btIgEzfWtrX3/tyBCaCvXvMkOw==",
      "dev": true
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmmirror.com/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/commander": {
      "version": "12.1.0",
      "resolved": "https://registry.npmmirror.com/commander/-/commander-12.1.0.tgz",
      "integrity": "sha512-Vw8qHK3bZM9y/P10u3Vib8o/DdkvA2OtPtZvD871QKjy74Wj1WSKFILMPRPSdUSx5RFK1arlJzEtA4PkFgnbuA==",
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/commondir": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/commondir/-/commondir-1.0.1.tgz",
      "integrity": "sha512-W9pAhw0ja1Edb5GVdIF1mjZw/ASI0AlShXM83UUGe2DVr5TdAPEA1OA8m/g8zWp9x6On7gqufY+FatDbC3MDQg==",
      "dev": true
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmmirror.com/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg=="
    },
    "node_modules/confbox": {
      "version": "0.1.8",
      "resolved": "https://registry.npmmirror.com/confbox/-/confbox-0.1.8.tgz",
      "integrity": "sha512-RMtmw0iFkeR4YV+fUOSucriAQNb9g8zFR52MWCtl+cCZOFRNL6zeB395vPzFhEjjn4fMxXudmELnl/KF/WrK6w==",
      "dev": true
    },
    "node_modules/config-chain": {
      "version": "1.1.13",
      "resolved": "https://registry.npmmirror.com/config-chain/-/config-chain-1.1.13.tgz",
      "integrity": "sha512-qj+f8APARXHrM0hraqXYb2/bOVSV4PvJQlNZ/DVj0QrmNM2q2euizkeuVckQ57J+W0mRH6Hvi+k50M4Jul2VRQ==",
      "dependencies": {
        "ini": "^1.3.4",
        "proto-list": "~1.2.1"
      }
    },
    "node_modules/configstore": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/configstore/-/configstore-7.0.0.tgz",
      "integrity": "sha512-yk7/5PN5im4qwz0WFZW3PXnzHgPu9mX29Y8uZ3aefe2lBPC1FYttWZRcaW9fKkT0pBCJyuQ2HfbmPVaODi9jcQ==",
      "dev": true,
      "dependencies": {
        "atomically": "^2.0.3",
        "dot-prop": "^9.0.0",
        "graceful-fs": "^4.2.11",
        "xdg-basedir": "^5.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/yeoman/configstore?sponsor=1"
      }
    },
    "node_modules/consola": {
      "version": "3.2.3",
      "resolved": "https://registry.npmmirror.com/consola/-/consola-3.2.3.tgz",
      "integrity": "sha512-I5qxpzLv+sJhTVEoLYNcTW+bThDCPsit0vLNKShZx6rLtpilNpmmeTPaeqJb9ZE9dV3DGaeby6Vuhrw38WjeyQ==",
      "dev": true,
      "engines": {
        "node": "^14.18.0 || >=16.10.0"
      }
    },
    "node_modules/content-disposition": {
      "version": "0.5.4",
      "resolved": "https://registry.npmmirror.com/content-disposition/-/content-disposition-0.5.4.tgz",
      "integrity": "sha512-FveZTNuGw04cxlAiWbzi6zTAL/lhehaWbTtgluJh4/E95DqMwTmha3KZN1aAWA8cFIhHzMZUvLevkw5Rqk+tSQ==",
      "dependencies": {
        "safe-buffer": "5.2.1"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/convert-source-map": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/convert-source-map/-/convert-source-map-2.0.0.tgz",
      "integrity": "sha512-Kvp459HrV2FEJ1CAsi1Ku+MY3kasH19TFykTz2xWmMeq6bk2NU3XXvfJ+Q61m0xktWwt+1HSYf3JZsTms3aRJg==",
      "dev": true
    },
    "node_modules/core-util-is": {
      "version": "1.0.3",
      "resolved": "https://registry.npmmirror.com/core-util-is/-/core-util-is-1.0.3.tgz",
      "integrity": "sha512-ZQBvi1DcpJ4GDqanjucZ2Hj3wEO5pZDS89BWbkcrvdxksJorwUDDZamX9ldFkp9aw2lmBDLgkObEA4DWNJ9FYQ=="
    },
    "node_modules/cosmiconfig": {
      "version": "9.0.0",
      "resolved": "https://registry.npmmirror.com/cosmiconfig/-/cosmiconfig-9.0.0.tgz",
      "integrity": "sha512-itvL5h8RETACmOTFc4UfIyB2RfEHi71Ax6E/PivVxq9NseKbOWpeyHEOIbmAw1rs8Ak0VursQNww7lf7YtUwzg==",
      "dev": true,
      "dependencies": {
        "env-paths": "^2.2.1",
        "import-fresh": "^3.3.0",
        "js-yaml": "^4.1.0",
        "parse-json": "^5.2.0"
      },
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/d-fischer"
      },
      "peerDependencies": {
        "typescript": ">=4.9.5"
      },
      "peerDependenciesMeta": {
        "typescript": {
          "optional": true
        }
      }
    },
    "node_modules/cross-spawn": {
      "version": "7.0.6",
      "resolved": "https://registry.npmmirror.com/cross-spawn/-/cross-spawn-7.0.6.tgz",
      "integrity": "sha512-uV2QOWP2nWzsy2aMp8aRibhi9dlzF5Hgh5SHaB9OiTGEyDTiJJyx0uy51QXdyWbtAHNua4XJzUKca3OzKUd3vA==",
      "dependencies": {
        "path-key": "^3.1.0",
        "shebang-command": "^2.0.0",
        "which": "^2.0.1"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/css-declaration-sorter": {
      "version": "7.2.0",
      "resolved": "https://registry.npmmirror.com/css-declaration-sorter/-/css-declaration-sorter-7.2.0.tgz",
      "integrity": "sha512-h70rUM+3PNFuaBDTLe8wF/cdWu+dOZmb7pJt8Z2sedYbAcQVQV/tEchueg3GWxwqS0cxtbxmaHEdkNACqcvsow==",
      "dev": true,
      "engines": {
        "node": "^14 || ^16 || >=18"
      },
      "peerDependencies": {
        "postcss": "^8.0.9"
      }
    },
    "node_modules/css-select": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/css-select/-/css-select-5.1.0.tgz",
      "integrity": "sha512-nwoRF1rvRRnnCqqY7updORDsuqKzqYJ28+oSMaJMMgOauh3fvwHqMS7EZpIPqK8GL+g9mKxF1vP/ZjSeNjEVHg==",
      "dev": true,
      "dependencies": {
        "boolbase": "^1.0.0",
        "css-what": "^6.1.0",
        "domhandler": "^5.0.2",
        "domutils": "^3.0.1",
        "nth-check": "^2.0.1"
      },
      "funding": {
        "url": "https://github.com/sponsors/fb55"
      }
    },
    "node_modules/css-tree": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/css-tree/-/css-tree-2.3.1.tgz",
      "integrity": "sha512-6Fv1DV/TYw//QF5IzQdqsNDjx/wc8TrMBZsqjL9eW01tWb7R7k/mq+/VXfJCl7SoD5emsJop9cOByJZfs8hYIw==",
      "dev": true,
      "dependencies": {
        "mdn-data": "2.0.30",
        "source-map-js": "^1.0.1"
      },
      "engines": {
        "node": "^10 || ^12.20.0 || ^14.13.0 || >=15.0.0"
      }
    },
    "node_modules/css-what": {
      "version": "6.1.0",
      "resolved": "https://registry.npmmirror.com/css-what/-/css-what-6.1.0.tgz",
      "integrity": "sha512-HTUrgRJ7r4dsZKU6GjmpfRK1O76h97Z8MfS1G0FozR+oF2kG6Vfe8JE6zwrkbxigziPHinCJ+gCPjA9EaBDtRw==",
      "dev": true,
      "engines": {
        "node": ">= 6"
      },
      "funding": {
        "url": "https://github.com/sponsors/fb55"
      }
    },
    "node_modules/cssesc": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/cssesc/-/cssesc-3.0.0.tgz",
      "integrity": "sha512-/Tb/JcjK111nNScGob5MNtsntNM1aCNUDipB/TkwZFhyDrrE47SOx/18wF2bbjgc3ZzCSKW1T5nt5EbFoAz/Vg==",
      "dev": true,
      "bin": {
        "cssesc": "bin/cssesc"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/cssnano": {
      "version": "7.0.6",
      "resolved": "https://registry.npmmirror.com/cssnano/-/cssnano-7.0.6.tgz",
      "integrity": "sha512-54woqx8SCbp8HwvNZYn68ZFAepuouZW4lTwiMVnBErM3VkO7/Sd4oTOt3Zz3bPx3kxQ36aISppyXj2Md4lg8bw==",
      "dev": true,
      "dependencies": {
        "cssnano-preset-default": "^7.0.6",
        "lilconfig": "^3.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/cssnano"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/cssnano-preset-default": {
      "version": "7.0.6",
      "resolved": "https://registry.npmmirror.com/cssnano-preset-default/-/cssnano-preset-default-7.0.6.tgz",
      "integrity": "sha512-ZzrgYupYxEvdGGuqL+JKOY70s7+saoNlHSCK/OGn1vB2pQK8KSET8jvenzItcY+kA7NoWvfbb/YhlzuzNKjOhQ==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "css-declaration-sorter": "^7.2.0",
        "cssnano-utils": "^5.0.0",
        "postcss-calc": "^10.0.2",
        "postcss-colormin": "^7.0.2",
        "postcss-convert-values": "^7.0.4",
        "postcss-discard-comments": "^7.0.3",
        "postcss-discard-duplicates": "^7.0.1",
        "postcss-discard-empty": "^7.0.0",
        "postcss-discard-overridden": "^7.0.0",
        "postcss-merge-longhand": "^7.0.4",
        "postcss-merge-rules": "^7.0.4",
        "postcss-minify-font-values": "^7.0.0",
        "postcss-minify-gradients": "^7.0.0",
        "postcss-minify-params": "^7.0.2",
        "postcss-minify-selectors": "^7.0.4",
        "postcss-normalize-charset": "^7.0.0",
        "postcss-normalize-display-values": "^7.0.0",
        "postcss-normalize-positions": "^7.0.0",
        "postcss-normalize-repeat-style": "^7.0.0",
        "postcss-normalize-string": "^7.0.0",
        "postcss-normalize-timing-functions": "^7.0.0",
        "postcss-normalize-unicode": "^7.0.2",
        "postcss-normalize-url": "^7.0.0",
        "postcss-normalize-whitespace": "^7.0.0",
        "postcss-ordered-values": "^7.0.1",
        "postcss-reduce-initial": "^7.0.2",
        "postcss-reduce-transforms": "^7.0.0",
        "postcss-svgo": "^7.0.1",
        "postcss-unique-selectors": "^7.0.3"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/cssnano-utils": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/cssnano-utils/-/cssnano-utils-5.0.0.tgz",
      "integrity": "sha512-Uij0Xdxc24L6SirFr25MlwC2rCFX6scyUmuKpzI+JQ7cyqDEwD42fJ0xfB3yLfOnRDU5LKGgjQ9FA6LYh76GWQ==",
      "dev": true,
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/csso": {
      "version": "5.0.5",
      "resolved": "https://registry.npmmirror.com/csso/-/csso-5.0.5.tgz",
      "integrity": "sha512-0LrrStPOdJj+SPCCrGhzryycLjwcgUSHBtxNA8aIDxf0GLsRh1cKYhB00Gd1lDOS4yGH69+SNn13+TWbVHETFQ==",
      "dev": true,
      "dependencies": {
        "css-tree": "~2.2.0"
      },
      "engines": {
        "node": "^10 || ^12.20.0 || ^14.13.0 || >=15.0.0",
        "npm": ">=7.0.0"
      }
    },
    "node_modules/csso/node_modules/css-tree": {
      "version": "2.2.1",
      "resolved": "https://registry.npmmirror.com/css-tree/-/css-tree-2.2.1.tgz",
      "integrity": "sha512-OA0mILzGc1kCOCSJerOeqDxDQ4HOh+G8NbOJFOTgOCzpw7fCBubk0fEyxp8AgOL/jvLgYA/uV0cMbe43ElF1JA==",
      "dev": true,
      "dependencies": {
        "mdn-data": "2.0.28",
        "source-map-js": "^1.0.1"
      },
      "engines": {
        "node": "^10 || ^12.20.0 || ^14.13.0 || >=15.0.0",
        "npm": ">=7.0.0"
      }
    },
    "node_modules/csso/node_modules/mdn-data": {
      "version": "2.0.28",
      "resolved": "https://registry.npmmirror.com/mdn-data/-/mdn-data-2.0.28.tgz",
      "integrity": "sha512-aylIc7Z9y4yzHYAJNuESG3hfhC+0Ibp/MAMiaOZgNv4pmEdFyfZhhhny4MNiAfWdBQ1RQ2mfDWmM1x8SvGyp8g==",
      "dev": true
    },
    "node_modules/data-uri-to-buffer": {
      "version": "6.0.2",
      "resolved": "https://registry.npmmirror.com/data-uri-to-buffer/-/data-uri-to-buffer-6.0.2.tgz",
      "integrity": "sha512-7hvf7/GW8e86rW0ptuwS3OcBGDjIi6SZva7hCyWC0yYry2cOPmLIjXAUHI6DK2HsnwJd9ifmt57i8eV2n4YNpw==",
      "dev": true,
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/debug": {
      "version": "4.3.7",
      "resolved": "https://registry.npmmirror.com/debug/-/debug-4.3.7.tgz",
      "integrity": "sha512-Er2nc/H7RrMXZBFCEim6TCmMk02Z8vLC2Rbi1KEBggpo0fS6l0S1nnapwmIi3yW/+GOJap1Krg4w0Hg80oCqgQ==",
      "dev": true,
      "dependencies": {
        "ms": "^2.1.3"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/decode-uri-component": {
      "version": "0.2.2",
      "resolved": "https://registry.npmmirror.com/decode-uri-component/-/decode-uri-component-0.2.2.tgz",
      "integrity": "sha512-FqUYQ+8o158GyGTrMFJms9qh3CqTKvAqgqsTnkLI8sKu0028orqBhxNMFkFen0zGyg6epACD32pjVk58ngIErQ==",
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/decompress": {
      "version": "4.2.1",
      "resolved": "https://registry.npmmirror.com/decompress/-/decompress-4.2.1.tgz",
      "integrity": "sha512-e48kc2IjU+2Zw8cTb6VZcJQ3lgVbS4uuB1TfCHbiZIP/haNXm+SVyhu+87jts5/3ROpd82GSVCoNs/z8l4ZOaQ==",
      "dependencies": {
        "decompress-tar": "^4.0.0",
        "decompress-tarbz2": "^4.0.0",
        "decompress-targz": "^4.0.0",
        "decompress-unzip": "^4.0.1",
        "graceful-fs": "^4.1.10",
        "make-dir": "^1.0.0",
        "pify": "^2.3.0",
        "strip-dirs": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-response": {
      "version": "3.3.0",
      "resolved": "https://registry.npmmirror.com/decompress-response/-/decompress-response-3.3.0.tgz",
      "integrity": "sha512-BzRPQuY1ip+qDonAOz42gRm/pg9F768C+npV/4JOsxRC2sq+Rlk+Q4ZCAsOhnIaMrgarILY+RMUIvMmmX1qAEA==",
      "dependencies": {
        "mimic-response": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-tar": {
      "version": "4.1.1",
      "resolved": "https://registry.npmmirror.com/decompress-tar/-/decompress-tar-4.1.1.tgz",
      "integrity": "sha512-JdJMaCrGpB5fESVyxwpCx4Jdj2AagLmv3y58Qy4GE6HMVjWz1FeVQk1Ct4Kye7PftcdOo/7U7UKzYBJgqnGeUQ==",
      "dependencies": {
        "file-type": "^5.2.0",
        "is-stream": "^1.1.0",
        "tar-stream": "^1.5.2"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-tar/node_modules/file-type": {
      "version": "5.2.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-5.2.0.tgz",
      "integrity": "sha512-Iq1nJ6D2+yIO4c8HHg4fyVb8mAJieo1Oloy1mLLaB2PvezNedhBVm+QU7g0qM42aiMbRXTxKKwGD17rjKNJYVQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-tarbz2": {
      "version": "4.1.1",
      "resolved": "https://registry.npmmirror.com/decompress-tarbz2/-/decompress-tarbz2-4.1.1.tgz",
      "integrity": "sha512-s88xLzf1r81ICXLAVQVzaN6ZmX4A6U4z2nMbOwobxkLoIIfjVMBg7TeguTUXkKeXni795B6y5rnvDw7rxhAq9A==",
      "dependencies": {
        "decompress-tar": "^4.1.0",
        "file-type": "^6.1.0",
        "is-stream": "^1.1.0",
        "seek-bzip": "^1.0.5",
        "unbzip2-stream": "^1.0.9"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-tarbz2/node_modules/file-type": {
      "version": "6.2.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-6.2.0.tgz",
      "integrity": "sha512-YPcTBDV+2Tm0VqjybVd32MHdlEGAtuxS3VAYsumFokDSMG+ROT5wawGlnHDoz7bfMcMDt9hxuXvXwoKUx2fkOg==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-targz": {
      "version": "4.1.1",
      "resolved": "https://registry.npmmirror.com/decompress-targz/-/decompress-targz-4.1.1.tgz",
      "integrity": "sha512-4z81Znfr6chWnRDNfFNqLwPvm4db3WuZkqV+UgXQzSngG3CEKdBkw5jrv3axjjL96glyiiKjsxJG3X6WBZwX3w==",
      "dependencies": {
        "decompress-tar": "^4.1.1",
        "file-type": "^5.2.0",
        "is-stream": "^1.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-targz/node_modules/file-type": {
      "version": "5.2.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-5.2.0.tgz",
      "integrity": "sha512-Iq1nJ6D2+yIO4c8HHg4fyVb8mAJieo1Oloy1mLLaB2PvezNedhBVm+QU7g0qM42aiMbRXTxKKwGD17rjKNJYVQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-unzip": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/decompress-unzip/-/decompress-unzip-4.0.1.tgz",
      "integrity": "sha512-1fqeluvxgnn86MOh66u8FjbtJpAFv5wgCT9Iw8rcBqQcCo5tO8eiJw7NNTrvt9n4CRBVq7CstiS922oPgyGLrw==",
      "dependencies": {
        "file-type": "^3.8.0",
        "get-stream": "^2.2.0",
        "pify": "^2.3.0",
        "yauzl": "^2.4.2"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/decompress-unzip/node_modules/file-type": {
      "version": "3.9.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-3.9.0.tgz",
      "integrity": "sha512-RLoqTXE8/vPmMuTI88DAzhMYC99I8BWv7zYP4A1puo5HIjEJ5EX48ighy4ZyKMG9EDXxBgW6e++cn7d1xuFghA==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/decompress-unzip/node_modules/get-stream": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/get-stream/-/get-stream-2.3.1.tgz",
      "integrity": "sha512-AUGhbbemXxrZJRD5cDvKtQxLuYaIbNtDTK8YqupCI393Q2KSTreEsLUN3ZxAWFGiKTzL6nKuzfcIvieflUX9qA==",
      "dependencies": {
        "object-assign": "^4.0.1",
        "pinkie-promise": "^2.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/decompress-unzip/node_modules/pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/pify/-/pify-2.3.0.tgz",
      "integrity": "sha512-udgsAY+fTnvv7kI7aaxbqwWNb0AHiB0qBO89PZKPkoTmGOgdbrHDKD+0B2X4uTfJ/FT1R09r9gTsjUjNJotuog==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/decompress/node_modules/pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/pify/-/pify-2.3.0.tgz",
      "integrity": "sha512-udgsAY+fTnvv7kI7aaxbqwWNb0AHiB0qBO89PZKPkoTmGOgdbrHDKD+0B2X4uTfJ/FT1R09r9gTsjUjNJotuog==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/deep-extend": {
      "version": "0.6.0",
      "resolved": "https://registry.npmmirror.com/deep-extend/-/deep-extend-0.6.0.tgz",
      "integrity": "sha512-LOHxIOaPYdHlJRtCQfDIVZtfw/ufM8+rVj649RIHzcm/vGwQRXFt6OPqIFWsm2XEMrNIEtWR64sY1LEKD2vAOA==",
      "dev": true,
      "engines": {
        "node": ">=4.0.0"
      }
    },
    "node_modules/deepmerge": {
      "version": "4.3.1",
      "resolved": "https://registry.npmmirror.com/deepmerge/-/deepmerge-4.3.1.tgz",
      "integrity": "sha512-3sUqbMEc77XqpdNO7FRyRog+eW3ph+GYCbj+rK+uYyRMuwsVy0rMiVtPn+QJlKFvWP/1PYpapqYn0Me2knFn+A==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/default-browser": {
      "version": "5.2.1",
      "resolved": "https://registry.npmmirror.com/default-browser/-/default-browser-5.2.1.tgz",
      "integrity": "sha512-WY/3TUME0x3KPYdRRxEJJvXRHV4PyPoUsxtZa78lwItwRQRHhd2U9xOscaT/YTf8uCXIAjeJOFBVEh/7FtD8Xg==",
      "dev": true,
      "dependencies": {
        "bundle-name": "^4.1.0",
        "default-browser-id": "^5.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/default-browser-id": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/default-browser-id/-/default-browser-id-5.0.0.tgz",
      "integrity": "sha512-A6p/pu/6fyBcA1TRz/GqWYPViplrftcW2gZC9q79ngNCKAeR/X3gcEdXQHl4KNXV+3wgIJ1CPkJQ3IHM6lcsyA==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/defaults": {
      "version": "1.0.4",
      "resolved": "https://registry.npmmirror.com/defaults/-/defaults-1.0.4.tgz",
      "integrity": "sha512-eFuaLoy/Rxalv2kr+lqMlUnrDWV+3j4pljOIJgLIhI058IQfWJ7vXhyEIHu+HtC738klGALYxOKDO0bQP3tg8A==",
      "dev": true,
      "dependencies": {
        "clone": "^1.0.2"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/define-lazy-prop": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/define-lazy-prop/-/define-lazy-prop-3.0.0.tgz",
      "integrity": "sha512-N+MeXYoqr3pOgn8xfyRPREN7gHakLYjhsHhWGT3fWAiL4IkAt0iDw14QiiEm2bE30c5XX5q0FtAA3CK5f9/BUg==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/defu": {
      "version": "6.1.4",
      "resolved": "https://registry.npmmirror.com/defu/-/defu-6.1.4.tgz",
      "integrity": "sha512-mEQCMmwJu317oSz8CwdIOdwf3xMif1ttiM8LTufzc3g6kR+9Pe236twL8j3IYT1F7GfRgGcW6MWxzZjLIkuHIg==",
      "dev": true
    },
    "node_modules/degenerator": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/degenerator/-/degenerator-5.0.1.tgz",
      "integrity": "sha512-TllpMR/t0M5sqCXfj85i4XaAzxmS5tVA16dqvdkMwGmzI+dXLXnw3J+3Vdv7VKw+ThlTMboK6i9rnZ6Nntj5CQ==",
      "dev": true,
      "dependencies": {
        "ast-types": "^0.13.4",
        "escodegen": "^2.1.0",
        "esprima": "^4.0.1"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/deprecation": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/deprecation/-/deprecation-2.3.1.tgz",
      "integrity": "sha512-xmHIy4F3scKVwMsQ4WnVaS8bHOx0DmVwRywosKhaILI0ywMDWPtBSku2HNxRvF7jtwDRsoEwYQSfbxj8b7RlJQ==",
      "dev": true
    },
    "node_modules/dir-glob": {
      "version": "3.0.1",
      "resolved": "https://registry.npmmirror.com/dir-glob/-/dir-glob-3.0.1.tgz",
      "integrity": "sha512-WkrWp9GR4KXfKGYzOLmTuGVi1UWFfws377n9cc55/tb6DuqyF6pcQ5AbiHEshaDpY9v6oaSr2XCDidGmMwdzIA==",
      "dev": true,
      "dependencies": {
        "path-type": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/dom-serializer": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/dom-serializer/-/dom-serializer-2.0.0.tgz",
      "integrity": "sha512-wIkAryiqt/nV5EQKqQpo3SToSOV9J0DnbJqwK7Wv/Trc92zIAYZ4FlMu+JPFW1DfGFt81ZTCGgDEabffXeLyJg==",
      "dev": true,
      "dependencies": {
        "domelementtype": "^2.3.0",
        "domhandler": "^5.0.2",
        "entities": "^4.2.0"
      },
      "funding": {
        "url": "https://github.com/cheeriojs/dom-serializer?sponsor=1"
      }
    },
    "node_modules/domelementtype": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/domelementtype/-/domelementtype-2.3.0.tgz",
      "integrity": "sha512-OLETBj6w0OsagBwdXnPdN0cnMfF9opN69co+7ZrbfPGrdpPVNBUj02spi6B1N7wChLQiPn4CSH/zJvXw56gmHw==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/fb55"
        }
      ]
    },
    "node_modules/domhandler": {
      "version": "5.0.3",
      "resolved": "https://registry.npmmirror.com/domhandler/-/domhandler-5.0.3.tgz",
      "integrity": "sha512-cgwlv/1iFQiFnU96XXgROh8xTeetsnJiDsTc7TYCLFd9+/WNkIqPTxiM/8pSd8VIrhXGTf1Ny1q1hquVqDJB5w==",
      "dev": true,
      "dependencies": {
        "domelementtype": "^2.3.0"
      },
      "engines": {
        "node": ">= 4"
      },
      "funding": {
        "url": "https://github.com/fb55/domhandler?sponsor=1"
      }
    },
    "node_modules/domutils": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/domutils/-/domutils-3.1.0.tgz",
      "integrity": "sha512-H78uMmQtI2AhgDJjWeQmHwJJ2bLPD3GMmO7Zja/ZZh84wkm+4ut+IUnUdRa8uCGX88DiVx1j6FRe1XfxEgjEZA==",
      "dev": true,
      "dependencies": {
        "dom-serializer": "^2.0.0",
        "domelementtype": "^2.3.0",
        "domhandler": "^5.0.3"
      },
      "funding": {
        "url": "https://github.com/fb55/domutils?sponsor=1"
      }
    },
    "node_modules/dot-prop": {
      "version": "9.0.0",
      "resolved": "https://registry.npmmirror.com/dot-prop/-/dot-prop-9.0.0.tgz",
      "integrity": "sha512-1gxPBJpI/pcjQhKgIU91II6Wkay+dLcN3M6rf2uwP8hRur3HtQXjVrdAK3sjC0piaEuxzMwjXChcETiJl47lAQ==",
      "dev": true,
      "dependencies": {
        "type-fest": "^4.18.2"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/dot-prop/node_modules/type-fest": {
      "version": "4.28.1",
      "resolved": "https://registry.npmmirror.com/type-fest/-/type-fest-4.28.1.tgz",
      "integrity": "sha512-LO/+yb3mf46YqfUC7QkkoAlpa7CTYh//V1Xy9+NQ+pKqDqXIq0NTfPfQRwFfCt+if4Qkwb9gzZfsl6E5TkXZGw==",
      "dev": true,
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/download": {
      "version": "7.1.0",
      "resolved": "https://registry.npmmirror.com/download/-/download-7.1.0.tgz",
      "integrity": "sha512-xqnBTVd/E+GxJVrX5/eUJiLYjCGPwMpdL+jGhGU57BvtcA7wwhtHVbXBeUk51kOpW3S7Jn3BQbN9Q1R1Km2qDQ==",
      "dependencies": {
        "archive-type": "^4.0.0",
        "caw": "^2.0.1",
        "content-disposition": "^0.5.2",
        "decompress": "^4.2.0",
        "ext-name": "^5.0.0",
        "file-type": "^8.1.0",
        "filenamify": "^2.0.0",
        "get-stream": "^3.0.0",
        "got": "^8.3.1",
        "make-dir": "^1.2.0",
        "p-event": "^2.1.0",
        "pify": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/download-git-repo": {
      "version": "3.0.2",
      "resolved": "https://registry.npmmirror.com/download-git-repo/-/download-git-repo-3.0.2.tgz",
      "integrity": "sha512-N8hWXD4hXqmEcNoR8TBYFntaOcYvEQ7Bz90mgm3bZRTuteGQqwT32VDMnTyD0KTEvb8BWrMc1tVmzuV9u/WrAg==",
      "dependencies": {
        "download": "^7.1.0",
        "git-clone": "^0.1.0",
        "rimraf": "^3.0.0"
      }
    },
    "node_modules/download-git-repo/node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmmirror.com/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/download-git-repo/node_modules/glob": {
      "version": "7.2.3",
      "resolved": "https://registry.npmmirror.com/glob/-/glob-7.2.3.tgz",
      "integrity": "sha512-nFR0zLpU2YCaRxwoCJvL6UvCH2JFyFVIvwTLsIf21AuHlMskA1hhTdk+LlYJtOlYt9v6dvszD2BGRqBL+iQK9Q==",
      "deprecated": "Glob versions prior to v9 are no longer supported",
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.1.1",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      },
      "engines": {
        "node": "*"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/download-git-repo/node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmmirror.com/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/download-git-repo/node_modules/rimraf": {
      "version": "3.0.2",
      "resolved": "https://registry.npmmirror.com/rimraf/-/rimraf-3.0.2.tgz",
      "integrity": "sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==",
      "deprecated": "Rimraf versions prior to v4 are no longer supported",
      "dependencies": {
        "glob": "^7.1.3"
      },
      "bin": {
        "rimraf": "bin.js"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/duplexer3": {
      "version": "0.1.5",
      "resolved": "https://registry.npmmirror.com/duplexer3/-/duplexer3-0.1.5.tgz",
      "integrity": "sha512-1A8za6ws41LQgv9HrE/66jyC5yuSjQ3L/KOpFtoBilsAK2iA2wuS5rTt1OCzIvtS2V7nVmedsUU+DGRcjBmOYA=="
    },
    "node_modules/eastasianwidth": {
      "version": "0.2.0",
      "resolved": "https://registry.npmmirror.com/eastasianwidth/-/eastasianwidth-0.2.0.tgz",
      "integrity": "sha512-I88TYZWc9XiYHRQ4/3c5rjjfgkjhLyW2luGIheGERbNQ6OY7yTybanSpDXZa8y7VUP9YmDcYa+eyq4ca7iLqWA=="
    },
    "node_modules/electron-to-chromium": {
      "version": "1.5.47",
      "resolved": "https://registry.npmmirror.com/electron-to-chromium/-/electron-to-chromium-1.5.47.tgz",
      "integrity": "sha512-zS5Yer0MOYw4rtK2iq43cJagHZ8sXN0jDHDKzB+86gSBSAI4v07S97mcq+Gs2vclAxSh1j7vOAHxSVgduiiuVQ==",
      "dev": true
    },
    "node_modules/emoji-regex": {
      "version": "10.4.0",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-10.4.0.tgz",
      "integrity": "sha512-EC+0oUMY1Rqm4O6LLrgjtYDvcVYTy7chDnM4Q7030tP4Kwj3u/pR6gP9ygnp2CJMK5Gq+9Q2oqmrFJAz01DXjw=="
    },
    "node_modules/end-of-stream": {
      "version": "1.4.4",
      "resolved": "https://registry.npmmirror.com/end-of-stream/-/end-of-stream-1.4.4.tgz",
      "integrity": "sha512-+uw1inIHVPQoaVuHzRyXd21icM+cnt4CzD5rW+NC1wjOUSTOs+Te7FOv7AhN7vS9x/oIyhLP5PR1H+phQAHu5Q==",
      "dependencies": {
        "once": "^1.4.0"
      }
    },
    "node_modules/entities": {
      "version": "4.5.0",
      "resolved": "https://registry.npmmirror.com/entities/-/entities-4.5.0.tgz",
      "integrity": "sha512-V0hjH4dGPh9Ao5p0MoRY6BVqtwCjhz6vI5LT8AJ55H+4g9/4vbHx1I54fS0XuclLhDHArPQCiMjDxjaL8fPxhw==",
      "dev": true,
      "engines": {
        "node": ">=0.12"
      },
      "funding": {
        "url": "https://github.com/fb55/entities?sponsor=1"
      }
    },
    "node_modules/env-paths": {
      "version": "2.2.1",
      "resolved": "https://registry.npmmirror.com/env-paths/-/env-paths-2.2.1.tgz",
      "integrity": "sha512-+h1lkLKhZMTYjog1VEpJNG7NZJWcuc2DDk/qsqSTRRCOXiLjeQ1d1/udrUGhqMxUgAlwKNZ0cf2uqan5GLuS2A==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/error-ex": {
      "version": "1.3.2",
      "resolved": "https://registry.npmmirror.com/error-ex/-/error-ex-1.3.2.tgz",
      "integrity": "sha512-7dFHNmqeFSEt2ZBsCriorKnn3Z2pj+fd9kmI6QoWw4//DL+icEBfc0U7qJCisqrTsKTjw4fNFy2pW9OqStD84g==",
      "dev": true,
      "dependencies": {
        "is-arrayish": "^0.2.1"
      }
    },
    "node_modules/esbuild": {
      "version": "0.19.12",
      "resolved": "https://registry.npmmirror.com/esbuild/-/esbuild-0.19.12.tgz",
      "integrity": "sha512-aARqgq8roFBj054KvQr5f1sFu0D65G+miZRCuJyJ0G13Zwx7vRar5Zhn2tkQNzIXcBrNVsv/8stehpj+GAjgbg==",
      "dev": true,
      "hasInstallScript": true,
      "bin": {
        "esbuild": "bin/esbuild"
      },
      "engines": {
        "node": ">=12"
      },
      "optionalDependencies": {
        "@esbuild/aix-ppc64": "0.19.12",
        "@esbuild/android-arm": "0.19.12",
        "@esbuild/android-arm64": "0.19.12",
        "@esbuild/android-x64": "0.19.12",
        "@esbuild/darwin-arm64": "0.19.12",
        "@esbuild/darwin-x64": "0.19.12",
        "@esbuild/freebsd-arm64": "0.19.12",
        "@esbuild/freebsd-x64": "0.19.12",
        "@esbuild/linux-arm": "0.19.12",
        "@esbuild/linux-arm64": "0.19.12",
        "@esbuild/linux-ia32": "0.19.12",
        "@esbuild/linux-loong64": "0.19.12",
        "@esbuild/linux-mips64el": "0.19.12",
        "@esbuild/linux-ppc64": "0.19.12",
        "@esbuild/linux-riscv64": "0.19.12",
        "@esbuild/linux-s390x": "0.19.12",
        "@esbuild/linux-x64": "0.19.12",
        "@esbuild/netbsd-x64": "0.19.12",
        "@esbuild/openbsd-x64": "0.19.12",
        "@esbuild/sunos-x64": "0.19.12",
        "@esbuild/win32-arm64": "0.19.12",
        "@esbuild/win32-ia32": "0.19.12",
        "@esbuild/win32-x64": "0.19.12"
      }
    },
    "node_modules/escalade": {
      "version": "3.2.0",
      "resolved": "https://registry.npmmirror.com/escalade/-/escalade-3.2.0.tgz",
      "integrity": "sha512-WUj2qlxaQtO4g6Pq5c29GTcWGDyd8itL8zTlipgECz3JesAiiOKotd8JU6otB3PACgG6xkJUyVhboMS+bje/jA==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/escape-goat": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/escape-goat/-/escape-goat-4.0.0.tgz",
      "integrity": "sha512-2Sd4ShcWxbx6OY1IHyla/CVNwvg7XwZVoXZHcSu9w9SReNP1EzzD5T8NWKIR38fIqEns9kDWKUQTXXAmlDrdPg==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/escape-string-regexp": {
      "version": "1.0.5",
      "resolved": "https://registry.npmmirror.com/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz",
      "integrity": "sha512-vbRorB5FUQWvla16U8R/qgaFIya2qGzwDrNmCZuYKrbdSUMG6I1ZCGQRefkRVhuOkIGVne7BQ35DSfo1qvJqFg==",
      "engines": {
        "node": ">=0.8.0"
      }
    },
    "node_modules/escodegen": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/escodegen/-/escodegen-2.1.0.tgz",
      "integrity": "sha512-2NlIDTwUWJN0mRPQOdtQBzbUHvdGY2P1VXSyU83Q3xKxM7WHX2Ql8dKq782Q9TgQUNOLEzEYu9bzLNj1q88I5w==",
      "dev": true,
      "dependencies": {
        "esprima": "^4.0.1",
        "estraverse": "^5.2.0",
        "esutils": "^2.0.2"
      },
      "bin": {
        "escodegen": "bin/escodegen.js",
        "esgenerate": "bin/esgenerate.js"
      },
      "engines": {
        "node": ">=6.0"
      },
      "optionalDependencies": {
        "source-map": "~0.6.1"
      }
    },
    "node_modules/esprima": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/esprima/-/esprima-4.0.1.tgz",
      "integrity": "sha512-eGuFFw7Upda+g4p+QHvnW0RyTX/SVeJBDM/gCtMARO0cLuT2HcEKnTPvhjV6aGeqrCB/sbNop0Kszm0jsaWU4A==",
      "dev": true,
      "bin": {
        "esparse": "bin/esparse.js",
        "esvalidate": "bin/esvalidate.js"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/estraverse": {
      "version": "5.3.0",
      "resolved": "https://registry.npmmirror.com/estraverse/-/estraverse-5.3.0.tgz",
      "integrity": "sha512-MMdARuVEQziNTeJD8DgMqmhwR11BRQ/cBP+pLtYdSTnf3MIO8fFeiINEbX36ZdNlfU/7A9f3gUw49B3oQsvwBA==",
      "dev": true,
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/estree-walker": {
      "version": "2.0.2",
      "resolved": "https://registry.npmmirror.com/estree-walker/-/estree-walker-2.0.2.tgz",
      "integrity": "sha512-Rfkk/Mp/DL7JVje3u18FxFujQlTNR2q6QfMSMB7AvCBx91NGj/ba3kCfza0f6dVDbw7YlRf/nDrn7pQrCCyQ/w==",
      "dev": true
    },
    "node_modules/esutils": {
      "version": "2.0.3",
      "resolved": "https://registry.npmmirror.com/esutils/-/esutils-2.0.3.tgz",
      "integrity": "sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/execa": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/execa/-/execa-8.0.0.tgz",
      "integrity": "sha512-CTNS0BcKBcoOsawKBlpcKNmK4Kjuyz5jVLhf+PUsHGMqiKMVTa4cN3U7r7bRY8KTpfOGpXMo27fdy0dYVg2pqA==",
      "dev": true,
      "dependencies": {
        "cross-spawn": "^7.0.3",
        "get-stream": "^8.0.1",
        "human-signals": "^5.0.0",
        "is-stream": "^3.0.0",
        "merge-stream": "^2.0.0",
        "npm-run-path": "^5.1.0",
        "onetime": "^6.0.0",
        "signal-exit": "^4.1.0",
        "strip-final-newline": "^3.0.0"
      },
      "engines": {
        "node": ">=16.17"
      },
      "funding": {
        "url": "https://github.com/sindresorhus/execa?sponsor=1"
      }
    },
    "node_modules/execa/node_modules/get-stream": {
      "version": "8.0.1",
      "resolved": "https://registry.npmmirror.com/get-stream/-/get-stream-8.0.1.tgz",
      "integrity": "sha512-VaUJspBffn/LMCJVoMvSAdmscJyS1auj5Zulnn5UoYcY531UWmdwhRWkcGKnGU93m5HSXP9LP2usOryrBtQowA==",
      "dev": true,
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/execa/node_modules/is-stream": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/is-stream/-/is-stream-3.0.0.tgz",
      "integrity": "sha512-LnQR4bZ9IADDRSkvpqMGvt/tEJWclzklNgSw48V5EAaAeDd6qGvN8ei6k5p0tvxSR171VmGyHuTiAOfxAbr8kA==",
      "dev": true,
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/execa/node_modules/onetime": {
      "version": "6.0.0",
      "resolved": "https://registry.npmmirror.com/onetime/-/onetime-6.0.0.tgz",
      "integrity": "sha512-1FlR+gjXK7X+AsAHso35MnyN5KqGwJRi/31ft6x0M194ht7S+rWAvd7PHss9xSKMzE0asv1pyIHaJYq+BbacAQ==",
      "dev": true,
      "dependencies": {
        "mimic-fn": "^4.0.0"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/ext-list": {
      "version": "2.2.2",
      "resolved": "https://registry.npmmirror.com/ext-list/-/ext-list-2.2.2.tgz",
      "integrity": "sha512-u+SQgsubraE6zItfVA0tBuCBhfU9ogSRnsvygI7wht9TS510oLkBRXBsqopeUG/GBOIQyKZO9wjTqIu/sf5zFA==",
      "dependencies": {
        "mime-db": "^1.28.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/ext-name": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/ext-name/-/ext-name-5.0.0.tgz",
      "integrity": "sha512-yblEwXAbGv1VQDmow7s38W77hzAgJAO50ztBLMcUyUBfxv1HC+LGwtiEN+Co6LtlqT/5uwVOxsD4TNIilWhwdQ==",
      "dependencies": {
        "ext-list": "^2.0.0",
        "sort-keys-length": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/external-editor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/external-editor/-/external-editor-3.1.0.tgz",
      "integrity": "sha512-hMQ4CX1p1izmuLYyZqLMO/qGNw10wSv9QDCPfzXfyFrOaCSSoRfqE1Kf1s5an66J5JZC62NewG+mK49jOCtQew==",
      "dev": true,
      "dependencies": {
        "chardet": "^0.7.0",
        "iconv-lite": "^0.4.24",
        "tmp": "^0.0.33"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/fast-glob": {
      "version": "3.3.2",
      "resolved": "https://registry.npmmirror.com/fast-glob/-/fast-glob-3.3.2.tgz",
      "integrity": "sha512-oX2ruAFQwf/Orj8m737Y5adxDQO0LAB7/S5MnxCdTNDd4p6BsyIVsv9JQsATbTSq8KHRpLwIHbVlUNatxd+1Ow==",
      "dev": true,
      "dependencies": {
        "@nodelib/fs.stat": "^2.0.2",
        "@nodelib/fs.walk": "^1.2.3",
        "glob-parent": "^5.1.2",
        "merge2": "^1.3.0",
        "micromatch": "^4.0.4"
      },
      "engines": {
        "node": ">=8.6.0"
      }
    },
    "node_modules/fastq": {
      "version": "1.17.1",
      "resolved": "https://registry.npmmirror.com/fastq/-/fastq-1.17.1.tgz",
      "integrity": "sha512-sRVD3lWVIXWg6By68ZN7vho9a1pQcN/WBFaAAsDDFzlJjvoGx0P8z7V1t72grFJfJhu3YPZBuu25f7Kaw2jN1w==",
      "dev": true,
      "dependencies": {
        "reusify": "^1.0.4"
      }
    },
    "node_modules/fd-slicer": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/fd-slicer/-/fd-slicer-1.1.0.tgz",
      "integrity": "sha512-cE1qsB/VwyQozZ+q1dGxR8LBYNZeofhEdUNGSMbQD3Gw2lAzX9Zb3uIU6Ebc/Fmyjo9AWWfnn0AUCHqtevs/8g==",
      "dependencies": {
        "pend": "~1.2.0"
      }
    },
    "node_modules/fdir": {
      "version": "6.4.2",
      "resolved": "https://registry.npmmirror.com/fdir/-/fdir-6.4.2.tgz",
      "integrity": "sha512-KnhMXsKSPZlAhp7+IjUkRZKPb4fUyccpDrdFXbi4QL1qkmFh9kVY09Yox+n4MaOb3lHZ1Tv829C3oaaXoMYPDQ==",
      "dev": true,
      "peerDependencies": {
        "picomatch": "^3 || ^4"
      },
      "peerDependenciesMeta": {
        "picomatch": {
          "optional": true
        }
      }
    },
    "node_modules/figlet": {
      "version": "1.8.0",
      "resolved": "https://registry.npmmirror.com/figlet/-/figlet-1.8.0.tgz",
      "integrity": "sha512-chzvGjd+Sp7KUvPHZv6EXV5Ir3Q7kYNpCr4aHrRW79qFtTefmQZNny+W1pW9kf5zeE6dikku2W50W/wAH2xWgw==",
      "dev": true,
      "bin": {
        "figlet": "bin/index.js"
      },
      "engines": {
        "node": ">= 0.4.0"
      }
    },
    "node_modules/file-type": {
      "version": "8.1.0",
      "resolved": "https://registry.npmmirror.com/file-type/-/file-type-8.1.0.tgz",
      "integrity": "sha512-qyQ0pzAy78gVoJsmYeNgl8uH8yKhr1lVhW7JbzJmnlRi0I4R2eEDEJZVKG8agpDnLpacwNbDhLNG/LMdxHD2YQ==",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/filename-reserved-regex": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/filename-reserved-regex/-/filename-reserved-regex-2.0.0.tgz",
      "integrity": "sha512-lc1bnsSr4L4Bdif8Xb/qrtokGbq5zlsms/CYH8PP+WtCkGNF65DPiQY8vG3SakEdRn8Dlnm+gW/qWKKjS5sZzQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/filenamify": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/filenamify/-/filenamify-2.1.0.tgz",
      "integrity": "sha512-ICw7NTT6RsDp2rnYKVd8Fu4cr6ITzGy3+u4vUujPkabyaz+03F24NWEX7fs5fp+kBonlaqPH8fAO2NM+SXt/JA==",
      "dependencies": {
        "filename-reserved-regex": "^2.0.0",
        "strip-outer": "^1.0.0",
        "trim-repeated": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/fill-range": {
      "version": "7.1.1",
      "resolved": "https://registry.npmmirror.com/fill-range/-/fill-range-7.1.1.tgz",
      "integrity": "sha512-YsGpe3WHLK8ZYi4tWDg2Jy3ebRz2rXowDxnld4bkQB00cc/1Zw9AWnC0i9ztDJitivtQvaI9KaLyKrc+hBW0yg==",
      "dev": true,
      "dependencies": {
        "to-regex-range": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/follow-redirects": {
      "version": "1.15.9",
      "resolved": "https://registry.npmmirror.com/follow-redirects/-/follow-redirects-1.15.9.tgz",
      "integrity": "sha512-gew4GsXizNgdoRyqmyfMHyAmXsZDk6mHkSxZFCzW9gwlbtOW44CDtYavM+y+72qD/Vq2l550kMF52DT8fOLJqQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/foreground-child": {
      "version": "3.3.0",
      "resolved": "https://registry.npmmirror.com/foreground-child/-/foreground-child-3.3.0.tgz",
      "integrity": "sha512-Ld2g8rrAyMYFXBhEqMz8ZAHBi4J4uS1i/CxGMDnjyFWddMXLVcDp051DZfu+t7+ab7Wv6SMqpWmyFIj5UbfFvg==",
      "dependencies": {
        "cross-spawn": "^7.0.0",
        "signal-exit": "^4.0.1"
      },
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/form-data": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/form-data/-/form-data-4.0.1.tgz",
      "integrity": "sha512-tzN8e4TX8+kkxGPK8D5u0FNmjPUjw3lwC9lSLxxoB/+GtsJG91CO8bSWy73APlgAZzZbXEYZJuxjkHH2w+Ezhw==",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/fraction.js": {
      "version": "4.3.7",
      "resolved": "https://registry.npmmirror.com/fraction.js/-/fraction.js-4.3.7.tgz",
      "integrity": "sha512-ZsDfxO51wGAXREY55a7la9LScWpwv9RxIrYABrlvOFBlH/ShPnrtsXeuUIfXKKOVicNxQ+o8JTbJvjS4M89yew==",
      "dev": true,
      "engines": {
        "node": "*"
      },
      "funding": {
        "type": "patreon",
        "url": "https://github.com/sponsors/rawify"
      }
    },
    "node_modules/from2": {
      "version": "2.3.0",
      "resolved": "https://registry.npmmirror.com/from2/-/from2-2.3.0.tgz",
      "integrity": "sha512-OMcX/4IC/uqEPVgGeyfN22LJk6AZrMkRZHxcHBMBvHScDGgwTm2GT2Wkgtocyd3JfZffjj2kYUDXXII0Fk9W0g==",
      "dependencies": {
        "inherits": "^2.0.1",
        "readable-stream": "^2.0.0"
      }
    },
    "node_modules/fs-constants": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/fs-constants/-/fs-constants-1.0.0.tgz",
      "integrity": "sha512-y6OAwoSIf7FyjMIv94u+b5rdheZEjzR63GTyZJm5qh4Bi+2YgwLCcI/fPFZkL5PSixOt6ZNKm+w+Hfp/Bciwow=="
    },
    "node_modules/fs-extra": {
      "version": "11.2.0",
      "resolved": "https://registry.npmmirror.com/fs-extra/-/fs-extra-11.2.0.tgz",
      "integrity": "sha512-PmDi3uwK5nFuXh7XDTlVnS17xJS7vW36is2+w3xcv8SVxiB4NyATf4ctkVY5bkSjX0Y4nbvZCq1/EjtEyr9ktw==",
      "dependencies": {
        "graceful-fs": "^4.2.0",
        "jsonfile": "^6.0.1",
        "universalify": "^2.0.0"
      },
      "engines": {
        "node": ">=14.14"
      }
    },
    "node_modules/fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha512-OO0pH2lK6a0hZnAdau5ItzHPI6pUlvI7jMVnxUQRtw4owF2wk8lOSabtGDCTP4Ggrg2MbGnWO9X8K1t4+fGMDw=="
    },
    "node_modules/fsevents": {
      "version": "2.3.3",
      "resolved": "https://registry.npmmirror.com/fsevents/-/fsevents-2.3.3.tgz",
      "integrity": "sha512-5xoDfX+fL7faATnagmWPpbFtwh/R77WmMMqqHGS65C3vvB0YHrgF+B1YmZ3441tMj5n63k0212XNoJwzlhffQw==",
      "dev": true,
      "hasInstallScript": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": "^8.16.0 || ^10.6.0 || >=11.0.0"
      }
    },
    "node_modules/function-bind": {
      "version": "1.1.2",
      "resolved": "https://registry.npmmirror.com/function-bind/-/function-bind-1.1.2.tgz",
      "integrity": "sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==",
      "dev": true,
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/gensync": {
      "version": "1.0.0-beta.2",
      "resolved": "https://registry.npmmirror.com/gensync/-/gensync-1.0.0-beta.2.tgz",
      "integrity": "sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==",
      "dev": true,
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/get-east-asian-width": {
      "version": "1.3.0",
      "resolved": "https://registry.npmmirror.com/get-east-asian-width/-/get-east-asian-width-1.3.0.tgz",
      "integrity": "sha512-vpeMIQKxczTD/0s2CdEWHcb0eeJe6TFjxb+J5xgX7hScxqrGuyjmv4c1D4A/gelKfyox0gJJwIHF+fLjeaM8kQ==",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/get-proxy": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/get-proxy/-/get-proxy-2.1.0.tgz",
      "integrity": "sha512-zmZIaQTWnNQb4R4fJUEp/FC51eZsc6EkErspy3xtIYStaq8EB/hDIWipxsal+E8rz0qD7f2sL/NA9Xee4RInJw==",
      "dependencies": {
        "npm-conf": "^1.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/get-stream": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/get-stream/-/get-stream-3.0.0.tgz",
      "integrity": "sha512-GlhdIUuVakc8SJ6kK0zAFbiGzRFzNnY4jUuEbV9UROo4Y+0Ny4fjvcZFVTeDA4odpFyOQzaw6hXukJSq/f28sQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/get-uri": {
      "version": "6.0.3",
      "resolved": "https://registry.npmmirror.com/get-uri/-/get-uri-6.0.3.tgz",
      "integrity": "sha512-BzUrJBS9EcUb4cFol8r4W3v1cPsSyajLSthNkz5BxbpDcHN5tIrM10E2eNvfnvBn3DaT3DUgx0OpsBKkaOpanw==",
      "dev": true,
      "dependencies": {
        "basic-ftp": "^5.0.2",
        "data-uri-to-buffer": "^6.0.2",
        "debug": "^4.3.4",
        "fs-extra": "^11.2.0"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/git-clone": {
      "version": "0.1.0",
      "resolved": "https://registry.npmmirror.com/git-clone/-/git-clone-0.1.0.tgz",
      "integrity": "sha512-zs9rlfa7HyaJAKG9o+V7C6qfMzyc+tb1IIXdUFcOBcR1U7siKy/uPdauLlrH1mc0vOgUwIv4BF+QxPiiTYz3Rw=="
    },
    "node_modules/git-up": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/git-up/-/git-up-7.0.0.tgz",
      "integrity": "sha512-ONdIrbBCFusq1Oy0sC71F5azx8bVkvtZtMJAsv+a6lz5YAmbNnLD6HAB4gptHZVLPR8S2/kVN6Gab7lryq5+lQ==",
      "dev": true,
      "dependencies": {
        "is-ssh": "^1.4.0",
        "parse-url": "^8.1.0"
      }
    },
    "node_modules/git-url-parse": {
      "version": "14.0.0",
      "resolved": "https://registry.npmmirror.com/git-url-parse/-/git-url-parse-14.0.0.tgz",
      "integrity": "sha512-NnLweV+2A4nCvn4U/m2AoYu0pPKlsmhK9cknG7IMwsjFY1S2jxM+mAhsDxyxfCIGfGaD+dozsyX4b6vkYc83yQ==",
      "dev": true,
      "dependencies": {
        "git-up": "^7.0.0"
      }
    },
    "node_modules/glob": {
      "version": "8.1.0",
      "resolved": "https://registry.npmmirror.com/glob/-/glob-8.1.0.tgz",
      "integrity": "sha512-r8hpEjiQEYlF2QU0df3dS+nxxSIreXQS1qRhMJM0Q5NDdR386C7jb7Hwwod8Fgiuex+k0GFjgft18yvxm5XoCQ==",
      "deprecated": "Glob versions prior to v9 are no longer supported",
      "dev": true,
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^5.0.1",
        "once": "^1.3.0"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/global-directory": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/global-directory/-/global-directory-4.0.1.tgz",
      "integrity": "sha512-wHTUcDUoZ1H5/0iVqEudYW4/kAlN5cZ3j/bXn0Dpbizl9iaUVeWSHqiOjsgk6OW2bkLclbBjzewBz6weQ1zA2Q==",
      "dev": true,
      "dependencies": {
        "ini": "4.1.1"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/global-directory/node_modules/ini": {
      "version": "4.1.1",
      "resolved": "https://registry.npmmirror.com/ini/-/ini-4.1.1.tgz",
      "integrity": "sha512-QQnnxNyfvmHFIsj7gkPcYymR8Jdw/o7mp5ZFihxn6h8Ci6fh3Dx4E1gPjpQEpIuPo9XVNY/ZUwh4BPMjGyL01g==",
      "dev": true,
      "engines": {
        "node": "^14.17.0 || ^16.13.0 || >=18.0.0"
      }
    },
    "node_modules/globals": {
      "version": "11.12.0",
      "resolved": "https://registry.npmmirror.com/globals/-/globals-11.12.0.tgz",
      "integrity": "sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/globby": {
      "version": "13.2.2",
      "resolved": "https://registry.npmmirror.com/globby/-/globby-13.2.2.tgz",
      "integrity": "sha512-Y1zNGV+pzQdh7H39l9zgB4PJqjRNqydvdYCDG4HFXM4XuvSaQQlEc91IU1yALL8gUTDomgBAfz3XJdmUS+oo0w==",
      "dev": true,
      "dependencies": {
        "dir-glob": "^3.0.1",
        "fast-glob": "^3.3.0",
        "ignore": "^5.2.4",
        "merge2": "^1.4.1",
        "slash": "^4.0.0"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/got": {
      "version": "8.3.2",
      "resolved": "https://registry.npmmirror.com/got/-/got-8.3.2.tgz",
      "integrity": "sha512-qjUJ5U/hawxosMryILofZCkm3C84PLJS/0grRIpjAwu+Lkxxj5cxeCU25BG0/3mDSpXKTyZr8oh8wIgLaH0QCw==",
      "dependencies": {
        "@sindresorhus/is": "^0.7.0",
        "cacheable-request": "^2.1.1",
        "decompress-response": "^3.3.0",
        "duplexer3": "^0.1.4",
        "get-stream": "^3.0.0",
        "into-stream": "^3.1.0",
        "is-retry-allowed": "^1.1.0",
        "isurl": "^1.0.0-alpha5",
        "lowercase-keys": "^1.0.0",
        "mimic-response": "^1.0.0",
        "p-cancelable": "^0.4.0",
        "p-timeout": "^2.0.1",
        "pify": "^3.0.0",
        "safe-buffer": "^5.1.1",
        "timed-out": "^4.0.1",
        "url-parse-lax": "^3.0.0",
        "url-to-options": "^1.0.1"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/graceful-fs": {
      "version": "4.2.11",
      "resolved": "https://registry.npmmirror.com/graceful-fs/-/graceful-fs-4.2.11.tgz",
      "integrity": "sha512-RbJ5/jmFcNNCcDV5o9eTnBLJ/HszWV0P73bc+Ff4nS/rJj+YaS6IGyiOL0VoBYX+l1Wrl3k63h/KrH+nhJ0XvQ=="
    },
    "node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/has-symbol-support-x": {
      "version": "1.4.2",
      "resolved": "https://registry.npmmirror.com/has-symbol-support-x/-/has-symbol-support-x-1.4.2.tgz",
      "integrity": "sha512-3ToOva++HaW+eCpgqZrCfN51IPB+7bJNVT6CUATzueB5Heb8o6Nam0V3HG5dlDvZU1Gn5QLcbahiKw/XVk5JJw==",
      "engines": {
        "node": "*"
      }
    },
    "node_modules/has-to-string-tag-x": {
      "version": "1.4.1",
      "resolved": "https://registry.npmmirror.com/has-to-string-tag-x/-/has-to-string-tag-x-1.4.1.tgz",
      "integrity": "sha512-vdbKfmw+3LoOYVr+mtxHaX5a96+0f3DljYd8JOqvOLsf5mw2Otda2qCDT9qRqLAhrjyQ0h7ual5nOiASpsGNFw==",
      "dependencies": {
        "has-symbol-support-x": "^1.4.1"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/hasown": {
      "version": "2.0.2",
      "resolved": "https://registry.npmmirror.com/hasown/-/hasown-2.0.2.tgz",
      "integrity": "sha512-0hJU9SCPvmMzIBdZFqNPXWa6dqh7WdH0cII9y+CyS8rG3nL48Bclra9HmKhVVUHyPWNH5Y7xDwAB7bfgSjkUMQ==",
      "dev": true,
      "dependencies": {
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/hookable": {
      "version": "5.5.3",
      "resolved": "https://registry.npmmirror.com/hookable/-/hookable-5.5.3.tgz",
      "integrity": "sha512-Yc+BQe8SvoXH1643Qez1zqLRmbA5rCL+sSmk6TVos0LWVfNIB7PGncdlId77WzLGSIB5KaWgTaNTs2lNVEI6VQ==",
      "dev": true
    },
    "node_modules/http-cache-semantics": {
      "version": "3.8.1",
      "resolved": "https://registry.npmmirror.com/http-cache-semantics/-/http-cache-semantics-3.8.1.tgz",
      "integrity": "sha512-5ai2iksyV8ZXmnZhHH4rWPoxxistEexSi5936zIQ1bnNTW5VnA85B6P/VpXiRM017IgRvb2kKo1a//y+0wSp3w=="
    },
    "node_modules/http-proxy-agent": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/http-proxy-agent/-/http-proxy-agent-7.0.2.tgz",
      "integrity": "sha512-T1gkAiYYDWYx3V5Bmyu7HcfcvL7mUrTWiM6yOfa3PIphViJ/gFPbvidQ+veqSOHci/PxBcDabeUNCzpOODJZig==",
      "dev": true,
      "dependencies": {
        "agent-base": "^7.1.0",
        "debug": "^4.3.4"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/https-proxy-agent": {
      "version": "7.0.5",
      "resolved": "https://registry.npmmirror.com/https-proxy-agent/-/https-proxy-agent-7.0.5.tgz",
      "integrity": "sha512-1e4Wqeblerz+tMKPIq2EMGiiWW1dIjZOksyHWSUm1rmuvw/how9hBHZ38lAGj5ID4Ik6EdkOw7NmWPy6LAwalw==",
      "dev": true,
      "dependencies": {
        "agent-base": "^7.0.2",
        "debug": "4"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/human-signals": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/human-signals/-/human-signals-5.0.0.tgz",
      "integrity": "sha512-AXcZb6vzzrFAUE61HnN4mpLqd/cSIwNQjtNWR0euPm6y0iqx3G4gOXaIDdtdDwZmhwe82LA6+zinmW4UBWVePQ==",
      "dev": true,
      "engines": {
        "node": ">=16.17.0"
      }
    },
    "node_modules/iconv-lite": {
      "version": "0.4.24",
      "resolved": "https://registry.npmmirror.com/iconv-lite/-/iconv-lite-0.4.24.tgz",
      "integrity": "sha512-v3MXnZAcvnywkTUEZomIActle7RXXeedOR31wwl7VlyoXO4Qi9arvSenNQWne1TcRwhCL1HwLI21bEqdpj8/rA==",
      "dev": true,
      "dependencies": {
        "safer-buffer": ">= 2.1.2 < 3"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/ieee754": {
      "version": "1.2.1",
      "resolved": "https://registry.npmmirror.com/ieee754/-/ieee754-1.2.1.tgz",
      "integrity": "sha512-dcyqhDvX1C46lXZcVqCpK+FtMRQVdIMN6/Df5js2zouUsqG7I6sFxitIC+7KYK29KdXOLHdu9zL4sFnoVQnqaA==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ]
    },
    "node_modules/ignore": {
      "version": "5.3.2",
      "resolved": "https://registry.npmmirror.com/ignore/-/ignore-5.3.2.tgz",
      "integrity": "sha512-hsBTNUqQTDwkWtcdYI2i06Y/nUBEsNEDJKjWdigLvegy8kDuJAS8uRlpkkcQpyEXL0Z/pjDy5HBmMjRCJ2gq+g==",
      "dev": true,
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/import-fresh": {
      "version": "3.3.0",
      "resolved": "https://registry.npmmirror.com/import-fresh/-/import-fresh-3.3.0.tgz",
      "integrity": "sha512-veYYhQa+D1QBKznvhUHxb8faxlrwUnxseDAbAp457E0wLNio2bOSKnjYDhMj+YiAq61xrMGhQk9iXVk5FzgQMw==",
      "dev": true,
      "dependencies": {
        "parent-module": "^1.0.0",
        "resolve-from": "^4.0.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmmirror.com/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha512-k92I/b08q4wvFscXCLvqfsHCrjrF7yiXsQuIVvVE7N82W3+aqpzuUdBbfhWcy/FZR3/4IgflMgKLOsvPDrGCJA==",
      "deprecated": "This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.",
      "dependencies": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "node_modules/inherits": {
      "version": "2.0.4",
      "resolved": "https://registry.npmmirror.com/inherits/-/inherits-2.0.4.tgz",
      "integrity": "sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ=="
    },
    "node_modules/ini": {
      "version": "1.3.8",
      "resolved": "https://registry.npmmirror.com/ini/-/ini-1.3.8.tgz",
      "integrity": "sha512-JV/yugV2uzW5iMRSiZAyDtQd+nxtUnjeLt0acNdw98kKLrvuRVyB80tsREOE7yvGVgalhZ6RNXCmEHkUKBKxew=="
    },
    "node_modules/inquirer": {
      "version": "9.3.2",
      "resolved": "https://registry.npmmirror.com/inquirer/-/inquirer-9.3.2.tgz",
      "integrity": "sha512-+ynEbhWKhyomnaX0n2aLIMSkgSlGB5RrWbNXnEqj6mdaIydu6y40MdBjL38SAB0JcdmOaIaMua1azdjLEr3sdw==",
      "dev": true,
      "dependencies": {
        "@inquirer/figures": "^1.0.3",
        "ansi-escapes": "^4.3.2",
        "cli-width": "^4.1.0",
        "external-editor": "^3.1.0",
        "mute-stream": "1.0.0",
        "ora": "^5.4.1",
        "run-async": "^3.0.0",
        "rxjs": "^7.8.1",
        "string-width": "^4.2.3",
        "strip-ansi": "^6.0.1",
        "wrap-ansi": "^6.2.0",
        "yoctocolors-cjs": "^2.1.1"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/inquirer/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmmirror.com/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/inquirer/node_modules/bl": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/bl/-/bl-4.1.0.tgz",
      "integrity": "sha512-1W07cM9gS6DcLperZfFSj+bWLtaPGSOHWhPiGzXmvVJbRLdG82sH/Kn8EtW1VqWVA54AKf2h5k5BbnIbwF3h6w==",
      "dev": true,
      "dependencies": {
        "buffer": "^5.5.0",
        "inherits": "^2.0.4",
        "readable-stream": "^3.4.0"
      }
    },
    "node_modules/inquirer/node_modules/chalk": {
      "version": "4.1.2",
      "resolved": "https://registry.npmmirror.com/chalk/-/chalk-4.1.2.tgz",
      "integrity": "sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/inquirer/node_modules/cli-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/cli-cursor/-/cli-cursor-3.1.0.tgz",
      "integrity": "sha512-I/zHAwsKf9FqGoXM4WWRACob9+SNukZTd94DWF57E4toouRulbCxcUh6RKUEOQlYTHJnzkPMySvPNaaSLNfLZw==",
      "dev": true,
      "dependencies": {
        "restore-cursor": "^3.1.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true
    },
    "node_modules/inquirer/node_modules/is-interactive": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/is-interactive/-/is-interactive-1.0.0.tgz",
      "integrity": "sha512-2HvIEKRoqS62guEC+qBjpvRubdX910WCMuJTZ+I9yvqKU2/12eSL549HMwtabb4oupdj2sMP50k+XJfB/8JE6w==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/is-unicode-supported": {
      "version": "0.1.0",
      "resolved": "https://registry.npmmirror.com/is-unicode-supported/-/is-unicode-supported-0.1.0.tgz",
      "integrity": "sha512-knxG2q4UC3u8stRGyAVJCOdxFmv5DZiRcdlIaAQXAbSfJya+OhopNotLQrstBhququ4ZpuKbDc/8S6mgXgPFPw==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/inquirer/node_modules/log-symbols": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/log-symbols/-/log-symbols-4.1.0.tgz",
      "integrity": "sha512-8XPvpAA8uyhfteu8pIvQxpJZ7SYYdpUivZpGy6sFsBuKRY/7rQGavedeB8aK+Zkyq6upMFVL/9AW6vOYzfRyLg==",
      "dev": true,
      "dependencies": {
        "chalk": "^4.1.0",
        "is-unicode-supported": "^0.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/inquirer/node_modules/mimic-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/mimic-fn/-/mimic-fn-2.1.0.tgz",
      "integrity": "sha512-OqbOk5oEQeAZ8WXWydlu9HJjz9WVdEIvamMCcXmuqUYjTknH/sqsWvhQ3vgwKFRR1HpjvNBKQ37nbJgYzGqGcg==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/inquirer/node_modules/onetime": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/onetime/-/onetime-5.1.2.tgz",
      "integrity": "sha512-kbpaSSGJTWdAY5KPVeMOKXSrPtr8C8C7wodJbcsd51jRnmD+GZu8Y0VoU6Dm5Z4vWr0Ig/1NKuWRKf7j5aaYSg==",
      "dev": true,
      "dependencies": {
        "mimic-fn": "^2.1.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/inquirer/node_modules/ora": {
      "version": "5.4.1",
      "resolved": "https://registry.npmmirror.com/ora/-/ora-5.4.1.tgz",
      "integrity": "sha512-5b6Y85tPxZZ7QytO+BQzysW31HJku27cRIlkbAXaNx+BdcVi+LlRFmVXzeF6a7JCwJpyw5c4b+YSVImQIrBpuQ==",
      "dev": true,
      "dependencies": {
        "bl": "^4.1.0",
        "chalk": "^4.1.0",
        "cli-cursor": "^3.1.0",
        "cli-spinners": "^2.5.0",
        "is-interactive": "^1.0.0",
        "is-unicode-supported": "^0.1.0",
        "log-symbols": "^4.1.0",
        "strip-ansi": "^6.0.0",
        "wcwidth": "^1.0.1"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/inquirer/node_modules/readable-stream": {
      "version": "3.6.2",
      "resolved": "https://registry.npmmirror.com/readable-stream/-/readable-stream-3.6.2.tgz",
      "integrity": "sha512-9u/sniCrY3D5WdsERHzHE4G2YCXqoG5FTHUiCC4SIbr6XcLZBY05ya9EKjYek9O5xOAwjGq+1JdGBAS7Q9ScoA==",
      "dev": true,
      "dependencies": {
        "inherits": "^2.0.3",
        "string_decoder": "^1.1.1",
        "util-deprecate": "^1.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/inquirer/node_modules/restore-cursor": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/restore-cursor/-/restore-cursor-3.1.0.tgz",
      "integrity": "sha512-l+sSefzHpj5qimhFSE5a8nufZYAM3sBSVMAPtYkmC+4EH2anSGaEMXSD0izRQbu9nfyQ9y5JrVmp7E8oZrUjvA==",
      "dev": true,
      "dependencies": {
        "onetime": "^5.1.0",
        "signal-exit": "^3.0.2"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/signal-exit": {
      "version": "3.0.7",
      "resolved": "https://registry.npmmirror.com/signal-exit/-/signal-exit-3.0.7.tgz",
      "integrity": "sha512-wnD2ZE+l+SPC/uoS0vXeE9L1+0wuaMqKlfz9AMUo38JsyLSBWSFcHR1Rri62LZc12vLr1gb3jl7iwQhgwpAbGQ==",
      "dev": true
    },
    "node_modules/inquirer/node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/inquirer/node_modules/wrap-ansi": {
      "version": "6.2.0",
      "resolved": "https://registry.npmmirror.com/wrap-ansi/-/wrap-ansi-6.2.0.tgz",
      "integrity": "sha512-r6lPcBGxZXlIcymEu7InxDMhdW0KDxpLgoFLcguasxCaJ/SOIZwINatK9KY/tf+ZrlywOKU0UDj3ATXUBfxJXA==",
      "dev": true,
      "dependencies": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/interpret": {
      "version": "1.4.0",
      "resolved": "https://registry.npmmirror.com/interpret/-/interpret-1.4.0.tgz",
      "integrity": "sha512-agE4QfB2Lkp9uICn7BAqoscw4SZP9kTE2hxiFI3jBPmXJfdqiahTbUuKGsMoN2GtqL9AxhYioAcVvgsb1HvRbA==",
      "dev": true,
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/into-stream": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/into-stream/-/into-stream-3.1.0.tgz",
      "integrity": "sha512-TcdjPibTksa1NQximqep2r17ISRiNE9fwlfbg3F8ANdvP5/yrFTew86VcO//jk4QTaMlbjypPBq76HN2zaKfZQ==",
      "dependencies": {
        "from2": "^2.1.1",
        "p-is-promise": "^1.1.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/ip-address": {
      "version": "9.0.5",
      "resolved": "https://registry.npmmirror.com/ip-address/-/ip-address-9.0.5.tgz",
      "integrity": "sha512-zHtQzGojZXTwZTHQqra+ETKd4Sn3vgi7uBmlPoXVWZqYvuKmtI0l/VZTjqGmJY9x88GGOaZ9+G9ES8hC4T4X8g==",
      "dev": true,
      "dependencies": {
        "jsbn": "1.1.0",
        "sprintf-js": "^1.1.3"
      },
      "engines": {
        "node": ">= 12"
      }
    },
    "node_modules/is-arrayish": {
      "version": "0.2.1",
      "resolved": "https://registry.npmmirror.com/is-arrayish/-/is-arrayish-0.2.1.tgz",
      "integrity": "sha512-zz06S8t0ozoDXMG+ube26zeCTNXcKIPJZJi8hBrF4idCLms4CG9QtK7qBl1boi5ODzFpjswb5JPmHCbMpjaYzg==",
      "dev": true
    },
    "node_modules/is-core-module": {
      "version": "2.15.1",
      "resolved": "https://registry.npmmirror.com/is-core-module/-/is-core-module-2.15.1.tgz",
      "integrity": "sha512-z0vtXSwucUJtANQWldhbtbt7BnL0vxiFjIdDLAatwhDYty2bad6s+rijD6Ri4YuYJubLzIJLUidCh09e1djEVQ==",
      "dev": true,
      "dependencies": {
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-docker": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/is-docker/-/is-docker-3.0.0.tgz",
      "integrity": "sha512-eljcgEDlEns/7AXFosB5K/2nCM4P7FQPkGc/DWLy5rmFEWvZayGrik1d9/QIY5nJ4f9YsVvBkA6kJpHn9rISdQ==",
      "dev": true,
      "bin": {
        "is-docker": "cli.js"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-extglob": {
      "version": "2.1.1",
      "resolved": "https://registry.npmmirror.com/is-extglob/-/is-extglob-2.1.1.tgz",
      "integrity": "sha512-SbKbANkN603Vi4jEZv49LeVJMn4yGwsbzZworEoyEiutsN3nJYdbO36zfhGJ6QEDpOZIFkDtnq5JRxmvl3jsoQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-glob": {
      "version": "4.0.3",
      "resolved": "https://registry.npmmirror.com/is-glob/-/is-glob-4.0.3.tgz",
      "integrity": "sha512-xelSayHH36ZgE7ZWhli7pW34hNbNl8Ojv5KVmkJD4hBdD3th8Tfk9vYasLM+mXWOZhFkgZfxhLSnrwRr4elSSg==",
      "dev": true,
      "dependencies": {
        "is-extglob": "^2.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-in-ci": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/is-in-ci/-/is-in-ci-1.0.0.tgz",
      "integrity": "sha512-eUuAjybVTHMYWm/U+vBO1sY/JOCgoPCXRxzdju0K+K0BiGW0SChEL1MLC0PoCIR1OlPo5YAp8HuQoUlsWEICwg==",
      "dev": true,
      "bin": {
        "is-in-ci": "cli.js"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-inside-container": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/is-inside-container/-/is-inside-container-1.0.0.tgz",
      "integrity": "sha512-KIYLCCJghfHZxqjYBE7rEy0OBuTd5xCHS7tHVgvCLkx7StIoaxwNW3hCALgEUjFfeRk+MG/Qxmp/vtETEF3tRA==",
      "dev": true,
      "dependencies": {
        "is-docker": "^3.0.0"
      },
      "bin": {
        "is-inside-container": "cli.js"
      },
      "engines": {
        "node": ">=14.16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-installed-globally": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/is-installed-globally/-/is-installed-globally-1.0.0.tgz",
      "integrity": "sha512-K55T22lfpQ63N4KEN57jZUAaAYqYHEe8veb/TycJRk9DdSCLLcovXz/mL6mOnhQaZsQGwPhuFopdQIlqGSEjiQ==",
      "dev": true,
      "dependencies": {
        "global-directory": "^4.0.1",
        "is-path-inside": "^4.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-interactive": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/is-interactive/-/is-interactive-2.0.0.tgz",
      "integrity": "sha512-qP1vozQRI+BMOPcjFzrjXuQvdak2pHNUMZoeG2eRbiSqyvbEf/wQtEOTOX1guk6E3t36RkaqiSt8A/6YElNxLQ==",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-module": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/is-module/-/is-module-1.0.0.tgz",
      "integrity": "sha512-51ypPSPCoTEIN9dy5Oy+h4pShgJmPCygKfyRCISBI+JoWT/2oJvK8QPxmwv7b/p239jXrm9M1mlQbyKJ5A152g==",
      "dev": true
    },
    "node_modules/is-natural-number": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/is-natural-number/-/is-natural-number-4.0.1.tgz",
      "integrity": "sha512-Y4LTamMe0DDQIIAlaer9eKebAlDSV6huy+TWhJVPlzZh2o4tRP5SQWFlLn5N0To4mDD22/qdOq+veo1cSISLgQ=="
    },
    "node_modules/is-npm": {
      "version": "6.0.0",
      "resolved": "https://registry.npmmirror.com/is-npm/-/is-npm-6.0.0.tgz",
      "integrity": "sha512-JEjxbSmtPSt1c8XTkVrlujcXdKV1/tvuQ7GwKcAlyiVLeYFQ2VHat8xfrDJsIkhCdF/tZ7CiIR3sy141c6+gPQ==",
      "dev": true,
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-number": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/is-number/-/is-number-7.0.0.tgz",
      "integrity": "sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==",
      "dev": true,
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/is-object": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/is-object/-/is-object-1.0.2.tgz",
      "integrity": "sha512-2rRIahhZr2UWb45fIOuvZGpFtz0TyOZLf32KxBbSoUCeZR495zCKlWUKKUByk3geS2eAs7ZAABt0Y/Rx0GiQGA==",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-path-inside": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/is-path-inside/-/is-path-inside-4.0.0.tgz",
      "integrity": "sha512-lJJV/5dYS+RcL8uQdBDW9c9uWFLLBNRyFhnAKXw5tVqLlKZ4RMGZKv+YQ/IA3OhD+RpbJa1LLFM1FQPGyIXvOA==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-plain-obj": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/is-plain-obj/-/is-plain-obj-1.1.0.tgz",
      "integrity": "sha512-yvkRyxmFKEOQ4pNXCmJG5AEQNlXJS5LaONXo5/cLdTZdWvsZ1ioJEonLGAosKlMWE8lwUy/bJzMjcw8az73+Fg==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-reference": {
      "version": "1.2.1",
      "resolved": "https://registry.npmmirror.com/is-reference/-/is-reference-1.2.1.tgz",
      "integrity": "sha512-U82MsXXiFIrjCK4otLT+o2NA2Cd2g5MLoOVXUZjIOhLurrRxpEXzI8O0KZHr3IjLvlAH1kTPYSuqer5T9ZVBKQ==",
      "dev": true,
      "dependencies": {
        "@types/estree": "*"
      }
    },
    "node_modules/is-retry-allowed": {
      "version": "1.2.0",
      "resolved": "https://registry.npmmirror.com/is-retry-allowed/-/is-retry-allowed-1.2.0.tgz",
      "integrity": "sha512-RUbUeKwvm3XG2VYamhJL1xFktgjvPzL0Hq8C+6yrWIswDy3BIXGqCxhxkc30N9jqK311gVU137K8Ei55/zVJRg==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-ssh": {
      "version": "1.4.0",
      "resolved": "https://registry.npmmirror.com/is-ssh/-/is-ssh-1.4.0.tgz",
      "integrity": "sha512-x7+VxdxOdlV3CYpjvRLBv5Lo9OJerlYanjwFrPR9fuGPjCiNiCzFgAWpiLAohSbsnH4ZAys3SBh+hq5rJosxUQ==",
      "dev": true,
      "dependencies": {
        "protocols": "^2.0.1"
      }
    },
    "node_modules/is-stream": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/is-stream/-/is-stream-1.1.0.tgz",
      "integrity": "sha512-uQPm8kcs47jx38atAcWTVxyltQYoPT68y9aWYdV6yWXSyW8mzSat0TL6CiWdZeCdF3KrAvpVtnHbTv4RN+rqdQ==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-unicode-supported": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/is-unicode-supported/-/is-unicode-supported-2.1.0.tgz",
      "integrity": "sha512-mE00Gnza5EEB3Ds0HfMyllZzbBrmLOX3vfWoj9A9PEnTfratQ/BcaJOuMhnkhjXvb2+FkY3VuHqtAGpTPmglFQ==",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/is-wsl": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/is-wsl/-/is-wsl-3.1.0.tgz",
      "integrity": "sha512-UcVfVfaK4Sc4m7X3dUSoHoozQGBEFeDC+zVo06t98xe8CzHSZZBekNXH+tu0NalHolcJ/QAGqS46Hef7QXBIMw==",
      "dev": true,
      "dependencies": {
        "is-inside-container": "^1.0.0"
      },
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha512-VLghIWNM6ELQzo7zwmcg0NmTVyWKYjvIeM83yjp0wRDTmUnrM678fQbcKBo6n2CJEF0szoG//ytg+TKla89ALQ=="
    },
    "node_modules/isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha512-RHxMLp9lnKHGHRng9QFhRCMbYAcVpn69smSGcq3f36xjgVVWThj4qqLbTLlq7Ssj8B+fIQ1EuCEGI2lKsyQeIw=="
    },
    "node_modules/issue-parser": {
      "version": "7.0.1",
      "resolved": "https://registry.npmmirror.com/issue-parser/-/issue-parser-7.0.1.tgz",
      "integrity": "sha512-3YZcUUR2Wt1WsapF+S/WiA2WmlW0cWAoPccMqne7AxEBhCdFeTPjfv/Axb8V2gyCgY3nRw+ksZ3xSUX+R47iAg==",
      "dev": true,
      "dependencies": {
        "lodash.capitalize": "^4.2.1",
        "lodash.escaperegexp": "^4.1.2",
        "lodash.isplainobject": "^4.0.6",
        "lodash.isstring": "^4.0.1",
        "lodash.uniqby": "^4.7.0"
      },
      "engines": {
        "node": "^18.17 || >=20.6.1"
      }
    },
    "node_modules/isurl": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/isurl/-/isurl-1.0.0.tgz",
      "integrity": "sha512-1P/yWsxPlDtn7QeRD+ULKQPaIaN6yF368GZ2vDfv0AL0NwpStafjWCDDdn0k8wgFMWpVAqG7oJhxHnlud42i9w==",
      "dependencies": {
        "has-to-string-tag-x": "^1.2.0",
        "is-object": "^1.0.1"
      },
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/jackspeak": {
      "version": "4.0.2",
      "resolved": "https://registry.npmmirror.com/jackspeak/-/jackspeak-4.0.2.tgz",
      "integrity": "sha512-bZsjR/iRjl1Nk1UkjGpAzLNfQtzuijhn2g+pbZb98HQ1Gk8vM9hfbxeMBP+M2/UUdwj0RqGG3mlvk2MsAqwvEw==",
      "dependencies": {
        "@isaacs/cliui": "^8.0.2"
      },
      "engines": {
        "node": "20 || >=22"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/jiti": {
      "version": "1.21.6",
      "resolved": "https://registry.npmmirror.com/jiti/-/jiti-1.21.6.tgz",
      "integrity": "sha512-2yTgeWTWzMWkHu6Jp9NKgePDaYHbntiwvYuuJLbbN9vl7DC9DvXKOB2BC3ZZ92D3cvV/aflH0osDfwpHepQ53w==",
      "dev": true,
      "bin": {
        "jiti": "bin/jiti.js"
      }
    },
    "node_modules/js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ==",
      "dev": true
    },
    "node_modules/js-yaml": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/js-yaml/-/js-yaml-4.1.0.tgz",
      "integrity": "sha512-wpxZs9NoxZaJESJGIZTyDEaYpl0FKSA+FB9aJiyemKhMwkxQg63h4T1KJgUGHpTqPDNRcmmYLugrRjJlBtWvRA==",
      "dev": true,
      "dependencies": {
        "argparse": "^2.0.1"
      },
      "bin": {
        "js-yaml": "bin/js-yaml.js"
      }
    },
    "node_modules/jsbn": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/jsbn/-/jsbn-1.1.0.tgz",
      "integrity": "sha512-4bYVV3aAMtDTTu4+xsDYa6sy9GyJ69/amsu9sYF2zqjiEoZA5xJi3BrfX3uY+/IekIu7MwdObdbDWpoZdBv3/A==",
      "dev": true
    },
    "node_modules/jsesc": {
      "version": "3.0.2",
      "resolved": "https://registry.npmmirror.com/jsesc/-/jsesc-3.0.2.tgz",
      "integrity": "sha512-xKqzzWXDttJuOcawBt4KnKHHIf5oQ/Cxax+0PWFG+DFDgHNAdi+TXECADI+RYiFUMmx8792xsMbbgXj4CwnP4g==",
      "dev": true,
      "bin": {
        "jsesc": "bin/jsesc"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/json-buffer": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/json-buffer/-/json-buffer-3.0.0.tgz",
      "integrity": "sha512-CuUqjv0FUZIdXkHPI8MezCnFCdaTAacej1TZYulLoAg1h/PhwkdXFN4V/gzY4g+fMBCOV2xF+rp7t2XD2ns/NQ=="
    },
    "node_modules/json-parse-even-better-errors": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/json-parse-even-better-errors/-/json-parse-even-better-errors-2.3.1.tgz",
      "integrity": "sha512-xyFwyhro/JEof6Ghe2iz2NcXoj2sloNsWr/XsERDK/oiPCfaNhl5ONfp+jQdAZRQQ0IJWNzH9zIZF7li91kh2w==",
      "dev": true
    },
    "node_modules/json5": {
      "version": "2.2.3",
      "resolved": "https://registry.npmmirror.com/json5/-/json5-2.2.3.tgz",
      "integrity": "sha512-XmOWe7eyHYH14cLdVPoyg+GOH3rYX++KpzrylJwSW98t3Nk+U8XOl8FWKOgwtzdb8lXGf6zYwDUzeHMWfxasyg==",
      "dev": true,
      "bin": {
        "json5": "lib/cli.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/jsonfile": {
      "version": "6.1.0",
      "resolved": "https://registry.npmmirror.com/jsonfile/-/jsonfile-6.1.0.tgz",
      "integrity": "sha512-5dgndWOriYSm5cnYaJNhalLNDKOqFwyDB/rr1E9ZsGciGvKPs8R2xYGCacuf3z6K1YKDz182fd+fY3cn3pMqXQ==",
      "dependencies": {
        "universalify": "^2.0.0"
      },
      "optionalDependencies": {
        "graceful-fs": "^4.1.6"
      }
    },
    "node_modules/keyv": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/keyv/-/keyv-3.0.0.tgz",
      "integrity": "sha512-eguHnq22OE3uVoSYG0LVWNP+4ppamWr9+zWBe1bsNcovIMy6huUJFPgy4mGwCd/rnl3vOLGW1MTlu4c57CT1xA==",
      "dependencies": {
        "json-buffer": "3.0.0"
      }
    },
    "node_modules/kleur": {
      "version": "3.0.3",
      "resolved": "https://registry.npmmirror.com/kleur/-/kleur-3.0.3.tgz",
      "integrity": "sha512-eTIzlVOSUR+JxdDFepEYcBMtZ9Qqdef+rnzWdRZuMbOywu5tO2w2N7rqjoANZ5k9vywhL6Br1VRjUIgTQx4E8w==",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/ky": {
      "version": "1.7.2",
      "resolved": "https://registry.npmmirror.com/ky/-/ky-1.7.2.tgz",
      "integrity": "sha512-OzIvbHKKDpi60TnF9t7UUVAF1B4mcqc02z5PIvrm08Wyb+yOcz63GRvEuVxNT18a9E1SrNouhB4W2NNLeD7Ykg==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sindresorhus/ky?sponsor=1"
      }
    },
    "node_modules/latest-version": {
      "version": "9.0.0",
      "resolved": "https://registry.npmmirror.com/latest-version/-/latest-version-9.0.0.tgz",
      "integrity": "sha512-7W0vV3rqv5tokqkBAFV1LbR7HPOWzXQDpDgEuib/aJ1jsZZx6x3c2mBI+TJhJzOhkGeaLbCKEHXEXLfirtG2JA==",
      "dev": true,
      "dependencies": {
        "package-json": "^10.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/lilconfig": {
      "version": "3.1.2",
      "resolved": "https://registry.npmmirror.com/lilconfig/-/lilconfig-3.1.2.tgz",
      "integrity": "sha512-eop+wDAvpItUys0FWkHIKeC9ybYrTGbU41U5K7+bttZZeohvnY7M9dZ5kB21GNWiFT2q1OoPTvncPCgSOVO5ow==",
      "dev": true,
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/antonk52"
      }
    },
    "node_modules/lines-and-columns": {
      "version": "1.2.4",
      "resolved": "https://registry.npmmirror.com/lines-and-columns/-/lines-and-columns-1.2.4.tgz",
      "integrity": "sha512-7ylylesZQ/PV29jhEDl3Ufjo6ZX7gCqJr5F7PKrqc93v7fzSymt1BpwEU8nAUXs8qzzvqhbjhK5QZg6Mt/HkBg==",
      "dev": true
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmmirror.com/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg==",
      "dev": true
    },
    "node_modules/lodash-es": {
      "version": "4.17.21",
      "resolved": "https://registry.npmmirror.com/lodash-es/-/lodash-es-4.17.21.tgz",
      "integrity": "sha512-mKnC+QJ9pWVzv+C4/U3rRsHapFfHvQFoFB92e52xeyGMcX6/OlIl78je1u8vePzYZSkkogMPJ2yjxxsb89cxyw=="
    },
    "node_modules/lodash.capitalize": {
      "version": "4.2.1",
      "resolved": "https://registry.npmmirror.com/lodash.capitalize/-/lodash.capitalize-4.2.1.tgz",
      "integrity": "sha512-kZzYOKspf8XVX5AvmQF94gQW0lejFVgb80G85bU4ZWzoJ6C03PQg3coYAUpSTpQWelrZELd3XWgHzw4Ck5kaIw==",
      "dev": true
    },
    "node_modules/lodash.escaperegexp": {
      "version": "4.1.2",
      "resolved": "https://registry.npmmirror.com/lodash.escaperegexp/-/lodash.escaperegexp-4.1.2.tgz",
      "integrity": "sha512-TM9YBvyC84ZxE3rgfefxUWiQKLilstD6k7PTGt6wfbtXF8ixIJLOL3VYyV/z+ZiPLsVxAsKAFVwWlWeb2Y8Yyw==",
      "dev": true
    },
    "node_modules/lodash.isplainobject": {
      "version": "4.0.6",
      "resolved": "https://registry.npmmirror.com/lodash.isplainobject/-/lodash.isplainobject-4.0.6.tgz",
      "integrity": "sha512-oSXzaWypCMHkPC3NvBEaPHf0KsA5mvPrOPgQWDsbg8n7orZ290M0BmC/jgRZ4vcJ6DTAhjrsSYgdsW/F+MFOBA==",
      "dev": true
    },
    "node_modules/lodash.isstring": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/lodash.isstring/-/lodash.isstring-4.0.1.tgz",
      "integrity": "sha512-0wJxfxH1wgO3GrbuP+dTTk7op+6L41QCXbGINEmD+ny/G/eCqGzxyCsh7159S+mgDDcoarnBw6PC1PS5+wUGgw==",
      "dev": true
    },
    "node_modules/lodash.memoize": {
      "version": "4.1.2",
      "resolved": "https://registry.npmmirror.com/lodash.memoize/-/lodash.memoize-4.1.2.tgz",
      "integrity": "sha512-t7j+NzmgnQzTAYXcsHYLgimltOV1MXHtlOWf6GjL9Kj8GK5FInw5JotxvbOs+IvV1/Dzo04/fCGfLVs7aXb4Ag==",
      "dev": true
    },
    "node_modules/lodash.uniq": {
      "version": "4.5.0",
      "resolved": "https://registry.npmmirror.com/lodash.uniq/-/lodash.uniq-4.5.0.tgz",
      "integrity": "sha512-xfBaXQd9ryd9dlSDvnvI0lvxfLJlYAZzXomUYzLKtUeOQvOP5piqAWuGtrhWeqaXK9hhoM/iyJc5AV+XfsX3HQ==",
      "dev": true
    },
    "node_modules/lodash.uniqby": {
      "version": "4.7.0",
      "resolved": "https://registry.npmmirror.com/lodash.uniqby/-/lodash.uniqby-4.7.0.tgz",
      "integrity": "sha512-e/zcLx6CSbmaEgFHCA7BnoQKyCtKMxnuWrJygbwPs/AIn+IMKl66L8/s+wBUn5LRw2pZx3bUHibiV1b6aTWIww==",
      "dev": true
    },
    "node_modules/log-symbols": {
      "version": "6.0.0",
      "resolved": "https://registry.npmmirror.com/log-symbols/-/log-symbols-6.0.0.tgz",
      "integrity": "sha512-i24m8rpwhmPIS4zscNzK6MSEhk0DUWa/8iYQWxhffV8jkI4Phvs3F+quL5xvS0gdQR0FyTCMMH33Y78dDTzzIw==",
      "dependencies": {
        "chalk": "^5.3.0",
        "is-unicode-supported": "^1.3.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/log-symbols/node_modules/is-unicode-supported": {
      "version": "1.3.0",
      "resolved": "https://registry.npmmirror.com/is-unicode-supported/-/is-unicode-supported-1.3.0.tgz",
      "integrity": "sha512-43r2mRvz+8JRIKnWJ+3j8JtjRKZ6GmjzfaE/qiBJnikNnYv/6bagRJ1kUhNk8R5EX/GkobD+r+sfxCPJsiKBLQ==",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/lowercase-keys": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/lowercase-keys/-/lowercase-keys-1.0.1.tgz",
      "integrity": "sha512-G2Lj61tXDnVFFOi8VZds+SoQjtQC3dgokKdDG2mTm1tx4m50NUHBOZSBwQQHyy0V12A0JTG4icfZQH+xPyh8VA==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/lru-cache": {
      "version": "5.1.1",
      "resolved": "https://registry.npmmirror.com/lru-cache/-/lru-cache-5.1.1.tgz",
      "integrity": "sha512-KpNARQA3Iwv+jTA0utUVVbrh+Jlrr1Fv0e56GGzAFOXN7dk/FviaDW8LHmK52DlcH4WP2n6gI8vN1aesBFgo9w==",
      "dev": true,
      "dependencies": {
        "yallist": "^3.0.2"
      }
    },
    "node_modules/macos-release": {
      "version": "3.3.0",
      "resolved": "https://registry.npmmirror.com/macos-release/-/macos-release-3.3.0.tgz",
      "integrity": "sha512-tPJQ1HeyiU2vRruNGhZ+VleWuMQRro8iFtJxYgnS4NQe+EukKF6aGiIT+7flZhISAt2iaXBCfFGvAyif7/f8nQ==",
      "dev": true,
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/magic-string": {
      "version": "0.30.12",
      "resolved": "https://registry.npmmirror.com/magic-string/-/magic-string-0.30.12.tgz",
      "integrity": "sha512-Ea8I3sQMVXr8JhN4z+H/d8zwo+tYDgHE9+5G4Wnrwhs0gaK9fXTKx0Tw5Xwsd/bCPTTZNRAdpyzvoeORe9LYpw==",
      "dev": true,
      "dependencies": {
        "@jridgewell/sourcemap-codec": "^1.5.0"
      }
    },
    "node_modules/make-dir": {
      "version": "1.3.0",
      "resolved": "https://registry.npmmirror.com/make-dir/-/make-dir-1.3.0.tgz",
      "integrity": "sha512-2w31R7SJtieJJnQtGc7RVL2StM2vGYVfqUOvUDxH6bC6aJTxPxTF0GnIgCyu7tjockiUWAYQRbxa7vKn34s5sQ==",
      "dependencies": {
        "pify": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/mdn-data": {
      "version": "2.0.30",
      "resolved": "https://registry.npmmirror.com/mdn-data/-/mdn-data-2.0.30.tgz",
      "integrity": "sha512-GaqWWShW4kv/G9IEucWScBx9G1/vsFZZJUO+tD26M8J8z3Kw5RDQjaoZe03YAClgeS/SWPOcb4nkFBTEi5DUEA==",
      "dev": true
    },
    "node_modules/merge-stream": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/merge-stream/-/merge-stream-2.0.0.tgz",
      "integrity": "sha512-abv/qOcuPfk3URPfDzmZU1LKmuw8kT+0nIHvKrKgFrwifol/doWcdA4ZqsWQ8ENrFKkd67Mfpo/LovbIUsbt3w==",
      "dev": true
    },
    "node_modules/merge2": {
      "version": "1.4.1",
      "resolved": "https://registry.npmmirror.com/merge2/-/merge2-1.4.1.tgz",
      "integrity": "sha512-8q7VEgMJW4J8tcfVPy8g09NcQwZdbwFEqhe/WZkoIzjn/3TGDwtOCYtXGxA3O8tPzpczCCDgv+P2P5y00ZJOOg==",
      "dev": true,
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/micromatch": {
      "version": "4.0.8",
      "resolved": "https://registry.npmmirror.com/micromatch/-/micromatch-4.0.8.tgz",
      "integrity": "sha512-PXwfBhYu0hBCPw8Dn0E+WDYb7af3dSLVWKi3HGv84IdF4TyFoC0ysxFd0Goxw7nSv4T/PzEJQxsYsEiFCKo2BA==",
      "dev": true,
      "dependencies": {
        "braces": "^3.0.3",
        "picomatch": "^2.3.1"
      },
      "engines": {
        "node": ">=8.6"
      }
    },
    "node_modules/micromatch/node_modules/picomatch": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/picomatch/-/picomatch-2.3.1.tgz",
      "integrity": "sha512-JU3teHTNjmE2VCGFzuY8EXzCDVwEqB2a8fsIvwaStHhAWJEeVd1o1QD80CU6+ZdEXXSLbSsuLwJjkCBWqRQUVA==",
      "dev": true,
      "engines": {
        "node": ">=8.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/jonschlinkert"
      }
    },
    "node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmmirror.com/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmmirror.com/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mimic-fn": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/mimic-fn/-/mimic-fn-4.0.0.tgz",
      "integrity": "sha512-vqiC06CuhBTUdZH+RYl8sFrL096vA45Ok5ISO6sE/Mr1jRbGH4Csnhi8f3wKVl7x8mO4Au7Ir9D3Oyv1VYMFJw==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/mimic-function": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/mimic-function/-/mimic-function-5.0.1.tgz",
      "integrity": "sha512-VP79XUPxV2CigYP3jWwAUFSku2aKqBH7uTAapFWCBqutsbmDo96KY5o8uh6U+/YSIn5OxJnXp73beVkpqMIGhA==",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/mimic-response": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/mimic-response/-/mimic-response-1.0.1.tgz",
      "integrity": "sha512-j5EctnkH7amfV/q5Hgmoal1g2QHFJRraOtmx0JpIqkxhBhI/lJSl1nMpQ45hVarwNETOoWEimndZ4QK0RHxuxQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/minimatch": {
      "version": "5.1.6",
      "resolved": "https://registry.npmmirror.com/minimatch/-/minimatch-5.1.6.tgz",
      "integrity": "sha512-lKwV/1brpG6mBUFHtb7NUmtABCb2WZZmm2wNiOA5hAb8VdCS4B3dtMWyvcoViccwAW/COERjXLt0zP1zXUN26g==",
      "dev": true,
      "dependencies": {
        "brace-expansion": "^2.0.1"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/minimist": {
      "version": "1.2.8",
      "resolved": "https://registry.npmmirror.com/minimist/-/minimist-1.2.8.tgz",
      "integrity": "sha512-2yyAR8qBkN3YuheJanUpWC5U3bb5osDywNB8RzDVlDwDHbocAJveqqj1u8+SVD7jkWT4yvsHCpWqqWqAxb0zCA==",
      "dev": true,
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/minipass": {
      "version": "7.1.2",
      "resolved": "https://registry.npmmirror.com/minipass/-/minipass-7.1.2.tgz",
      "integrity": "sha512-qOOzS1cBTWYF4BH8fVePDBOO9iptMnGUEZwNc/cMWnTV2nVLZ7VoNWEPHkYczZA0pdoA7dl6e7FL659nX9S2aw==",
      "engines": {
        "node": ">=16 || 14 >=14.17"
      }
    },
    "node_modules/mkcert": {
      "version": "3.2.0",
      "resolved": "https://registry.npmmirror.com/mkcert/-/mkcert-3.2.0.tgz",
      "integrity": "sha512-026Eivq9RoOjOuLJGzbhGwXUAjBxRX11Z7Jbm4/7lqT/Av+XNy9SPrJte6+UpEt7i+W3e/HZYxQqlQcqXZWSzg==",
      "dependencies": {
        "commander": "^11.0.0",
        "node-forge": "^1.3.1"
      },
      "bin": {
        "mkcert": "dist/cli.js"
      },
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/mkcert/node_modules/commander": {
      "version": "11.1.0",
      "resolved": "https://registry.npmmirror.com/commander/-/commander-11.1.0.tgz",
      "integrity": "sha512-yPVavfyCcRhmorC7rWlkHn15b4wDVgVmBA7kV4QVBsF7kv/9TKJAbAXVTxvTnwP8HHKjRCJDClKbciiYS7p0DQ==",
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/mkdist": {
      "version": "1.6.0",
      "resolved": "https://registry.npmmirror.com/mkdist/-/mkdist-1.6.0.tgz",
      "integrity": "sha512-nD7J/mx33Lwm4Q4qoPgRBVA9JQNKgyE7fLo5vdPWVDdjz96pXglGERp/fRnGPCTB37Kykfxs5bDdXa9BWOT9nw==",
      "dev": true,
      "dependencies": {
        "autoprefixer": "^10.4.20",
        "citty": "^0.1.6",
        "cssnano": "^7.0.6",
        "defu": "^6.1.4",
        "esbuild": "^0.24.0",
        "jiti": "^1.21.6",
        "mlly": "^1.7.1",
        "pathe": "^1.1.2",
        "pkg-types": "^1.2.0",
        "postcss": "^8.4.45",
        "postcss-nested": "^6.2.0",
        "semver": "^7.6.3",
        "tinyglobby": "^0.2.9"
      },
      "bin": {
        "mkdist": "dist/cli.cjs"
      },
      "peerDependencies": {
        "sass": "^1.78.0",
        "typescript": ">=5.5.4",
        "vue-tsc": "^1.8.27 || ^2.0.21"
      },
      "peerDependenciesMeta": {
        "sass": {
          "optional": true
        },
        "typescript": {
          "optional": true
        },
        "vue-tsc": {
          "optional": true
        }
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/aix-ppc64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/aix-ppc64/-/aix-ppc64-0.24.0.tgz",
      "integrity": "sha512-WtKdFM7ls47zkKHFVzMz8opM7LkcsIp9amDUBIAWirg70RM71WRSjdILPsY5Uv1D42ZpUfaPILDlfactHgsRkw==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/android-arm": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-arm/-/android-arm-0.24.0.tgz",
      "integrity": "sha512-arAtTPo76fJ/ICkXWetLCc9EwEHKaeya4vMrReVlEIUCAUncH7M4bhMQ+M9Vf+FFOZJdTNMXNBrWwW+OXWpSew==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/android-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-arm64/-/android-arm64-0.24.0.tgz",
      "integrity": "sha512-Vsm497xFM7tTIPYK9bNTYJyF/lsP590Qc1WxJdlB6ljCbdZKU9SY8i7+Iin4kyhV/KV5J2rOKsBQbB77Ab7L/w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/android-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/android-x64/-/android-x64-0.24.0.tgz",
      "integrity": "sha512-t8GrvnFkiIY7pa7mMgJd7p8p8qqYIz1NYiAoKc75Zyv73L3DZW++oYMSHPRarcotTKuSs6m3hTOa5CKHaS02TQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/darwin-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/darwin-arm64/-/darwin-arm64-0.24.0.tgz",
      "integrity": "sha512-CKyDpRbK1hXwv79soeTJNHb5EiG6ct3efd/FTPdzOWdbZZfGhpbcqIpiD0+vwmpu0wTIL97ZRPZu8vUt46nBSw==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/darwin-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/darwin-x64/-/darwin-x64-0.24.0.tgz",
      "integrity": "sha512-rgtz6flkVkh58od4PwTRqxbKH9cOjaXCMZgWD905JOzjFKW+7EiUObfd/Kav+A6Gyud6WZk9w+xu6QLytdi2OA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/freebsd-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/freebsd-arm64/-/freebsd-arm64-0.24.0.tgz",
      "integrity": "sha512-6Mtdq5nHggwfDNLAHkPlyLBpE5L6hwsuXZX8XNmHno9JuL2+bg2BX5tRkwjyfn6sKbxZTq68suOjgWqCicvPXA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/freebsd-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/freebsd-x64/-/freebsd-x64-0.24.0.tgz",
      "integrity": "sha512-D3H+xh3/zphoX8ck4S2RxKR6gHlHDXXzOf6f/9dbFt/NRBDIE33+cVa49Kil4WUjxMGW0ZIYBYtaGCa2+OsQwQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-arm": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-arm/-/linux-arm-0.24.0.tgz",
      "integrity": "sha512-gJKIi2IjRo5G6Glxb8d3DzYXlxdEj2NlkixPsqePSZMhLudqPhtZ4BUrpIuTjJYXxvF9njql+vRjB2oaC9XpBw==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-arm64/-/linux-arm64-0.24.0.tgz",
      "integrity": "sha512-TDijPXTOeE3eaMkRYpcy3LarIg13dS9wWHRdwYRnzlwlA370rNdZqbcp0WTyyV/k2zSxfko52+C7jU5F9Tfj1g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-ia32": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-ia32/-/linux-ia32-0.24.0.tgz",
      "integrity": "sha512-K40ip1LAcA0byL05TbCQ4yJ4swvnbzHscRmUilrmP9Am7//0UjPreh4lpYzvThT2Quw66MhjG//20mrufm40mA==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-loong64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-loong64/-/linux-loong64-0.24.0.tgz",
      "integrity": "sha512-0mswrYP/9ai+CU0BzBfPMZ8RVm3RGAN/lmOMgW4aFUSOQBjA31UP8Mr6DDhWSuMwj7jaWOT0p0WoZ6jeHhrD7g==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-mips64el": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-mips64el/-/linux-mips64el-0.24.0.tgz",
      "integrity": "sha512-hIKvXm0/3w/5+RDtCJeXqMZGkI2s4oMUGj3/jM0QzhgIASWrGO5/RlzAzm5nNh/awHE0A19h/CvHQe6FaBNrRA==",
      "cpu": [
        "mips64el"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-ppc64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-ppc64/-/linux-ppc64-0.24.0.tgz",
      "integrity": "sha512-HcZh5BNq0aC52UoocJxaKORfFODWXZxtBaaZNuN3PUX3MoDsChsZqopzi5UupRhPHSEHotoiptqikjN/B77mYQ==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-riscv64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-riscv64/-/linux-riscv64-0.24.0.tgz",
      "integrity": "sha512-bEh7dMn/h3QxeR2KTy1DUszQjUrIHPZKyO6aN1X4BCnhfYhuQqedHaa5MxSQA/06j3GpiIlFGSsy1c7Gf9padw==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-s390x": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-s390x/-/linux-s390x-0.24.0.tgz",
      "integrity": "sha512-ZcQ6+qRkw1UcZGPyrCiHHkmBaj9SiCD8Oqd556HldP+QlpUIe2Wgn3ehQGVoPOvZvtHm8HPx+bH20c9pvbkX3g==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/linux-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/linux-x64/-/linux-x64-0.24.0.tgz",
      "integrity": "sha512-vbutsFqQ+foy3wSSbmjBXXIJ6PL3scghJoM8zCL142cGaZKAdCZHyf+Bpu/MmX9zT9Q0zFBVKb36Ma5Fzfa8xA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/netbsd-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/netbsd-x64/-/netbsd-x64-0.24.0.tgz",
      "integrity": "sha512-hjQ0R/ulkO8fCYFsG0FZoH+pWgTTDreqpqY7UnQntnaKv95uP5iW3+dChxnx7C3trQQU40S+OgWhUVwCjVFLvg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/openbsd-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/openbsd-x64/-/openbsd-x64-0.24.0.tgz",
      "integrity": "sha512-4ir0aY1NGUhIC1hdoCzr1+5b43mw99uNwVzhIq1OY3QcEwPDO3B7WNXBzaKY5Nsf1+N11i1eOfFcq+D/gOS15Q==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/sunos-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/sunos-x64/-/sunos-x64-0.24.0.tgz",
      "integrity": "sha512-jVzdzsbM5xrotH+W5f1s+JtUy1UWgjU0Cf4wMvffTB8m6wP5/kx0KiaLHlbJO+dMgtxKV8RQ/JvtlFcdZ1zCPA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/win32-arm64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-arm64/-/win32-arm64-0.24.0.tgz",
      "integrity": "sha512-iKc8GAslzRpBytO2/aN3d2yb2z8XTVfNV0PjGlCxKo5SgWmNXx82I/Q3aG1tFfS+A2igVCY97TJ8tnYwpUWLCA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/win32-ia32": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-ia32/-/win32-ia32-0.24.0.tgz",
      "integrity": "sha512-vQW36KZolfIudCcTnaTpmLQ24Ha1RjygBo39/aLkM2kmjkWmZGEJ5Gn9l5/7tzXA42QGIoWbICfg6KLLkIw6yw==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/@esbuild/win32-x64": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/@esbuild/win32-x64/-/win32-x64-0.24.0.tgz",
      "integrity": "sha512-7IAFPrjSQIJrGsK6flwg7NFmwBoSTyF3rl7If0hNUFQU4ilTsEPL6GuMuU9BfIWVVGuRnuIidkSMC+c0Otu8IA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/mkdist/node_modules/esbuild": {
      "version": "0.24.0",
      "resolved": "https://registry.npmmirror.com/esbuild/-/esbuild-0.24.0.tgz",
      "integrity": "sha512-FuLPevChGDshgSicjisSooU0cemp/sGXR841D5LHMB7mTVOmsEHcAxaH3irL53+8YDIeVNQEySh4DaYU/iuPqQ==",
      "dev": true,
      "hasInstallScript": true,
      "bin": {
        "esbuild": "bin/esbuild"
      },
      "engines": {
        "node": ">=18"
      },
      "optionalDependencies": {
        "@esbuild/aix-ppc64": "0.24.0",
        "@esbuild/android-arm": "0.24.0",
        "@esbuild/android-arm64": "0.24.0",
        "@esbuild/android-x64": "0.24.0",
        "@esbuild/darwin-arm64": "0.24.0",
        "@esbuild/darwin-x64": "0.24.0",
        "@esbuild/freebsd-arm64": "0.24.0",
        "@esbuild/freebsd-x64": "0.24.0",
        "@esbuild/linux-arm": "0.24.0",
        "@esbuild/linux-arm64": "0.24.0",
        "@esbuild/linux-ia32": "0.24.0",
        "@esbuild/linux-loong64": "0.24.0",
        "@esbuild/linux-mips64el": "0.24.0",
        "@esbuild/linux-ppc64": "0.24.0",
        "@esbuild/linux-riscv64": "0.24.0",
        "@esbuild/linux-s390x": "0.24.0",
        "@esbuild/linux-x64": "0.24.0",
        "@esbuild/netbsd-x64": "0.24.0",
        "@esbuild/openbsd-arm64": "0.24.0",
        "@esbuild/openbsd-x64": "0.24.0",
        "@esbuild/sunos-x64": "0.24.0",
        "@esbuild/win32-arm64": "0.24.0",
        "@esbuild/win32-ia32": "0.24.0",
        "@esbuild/win32-x64": "0.24.0"
      }
    },
    "node_modules/mlly": {
      "version": "1.7.2",
      "resolved": "https://registry.npmmirror.com/mlly/-/mlly-1.7.2.tgz",
      "integrity": "sha512-tN3dvVHYVz4DhSXinXIk7u9syPYaJvio118uomkovAtWBT+RdbP6Lfh/5Lvo519YMmwBafwlh20IPTXIStscpA==",
      "dev": true,
      "dependencies": {
        "acorn": "^8.12.1",
        "pathe": "^1.1.2",
        "pkg-types": "^1.2.0",
        "ufo": "^1.5.4"
      }
    },
    "node_modules/mri": {
      "version": "1.2.0",
      "resolved": "https://registry.npmmirror.com/mri/-/mri-1.2.0.tgz",
      "integrity": "sha512-tzzskb3bG8LvYGFF/mDTpq3jpI6Q9wc3LEmBaghu+DdCssd1FakN7Bc0hVNmEyGq1bq3RgfkCb3cmQLpNPOroA==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/ms": {
      "version": "2.1.3",
      "resolved": "https://registry.npmmirror.com/ms/-/ms-2.1.3.tgz",
      "integrity": "sha512-6FlzubTLZG3J2a/NVCAleEhjzq5oxgHyaCU9yYXvcLsvoVaHJq/s5xXI6/XXP6tz7R9xAOtHnSO/tXtF3WRTlA==",
      "dev": true
    },
    "node_modules/mute-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/mute-stream/-/mute-stream-1.0.0.tgz",
      "integrity": "sha512-avsJQhyd+680gKXyG/sQc0nXaC6rBkPOfyHYcFb9+hdkqQkR9bdnkJ0AMZhke0oesPqIO+mFFJ+IdBc7mst4IA==",
      "dev": true,
      "engines": {
        "node": "^14.17.0 || ^16.13.0 || >=18.0.0"
      }
    },
    "node_modules/nanoid": {
      "version": "3.3.7",
      "resolved": "https://registry.npmmirror.com/nanoid/-/nanoid-3.3.7.tgz",
      "integrity": "sha512-eSRppjcPIatRIMC1U6UngP8XFcz8MQWGQdt1MTBQ7NaAmvXDfvNxbvWV3x2y6CdEUciCSsDHDQZbhYaB8QEo2g==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "bin": {
        "nanoid": "bin/nanoid.cjs"
      },
      "engines": {
        "node": "^10 || ^12 || ^13.7 || ^14 || >=15.0.1"
      }
    },
    "node_modules/netmask": {
      "version": "2.0.2",
      "resolved": "https://registry.npmmirror.com/netmask/-/netmask-2.0.2.tgz",
      "integrity": "sha512-dBpDMdxv9Irdq66304OLfEmQ9tbNRFnFTuZiLo+bD+r332bBmMJ8GBLXklIXXgxd3+v9+KUnZaUR5PJMa75Gsg==",
      "dev": true,
      "engines": {
        "node": ">= 0.4.0"
      }
    },
    "node_modules/new-github-release-url": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/new-github-release-url/-/new-github-release-url-2.0.0.tgz",
      "integrity": "sha512-NHDDGYudnvRutt/VhKFlX26IotXe1w0cmkDm6JGquh5bz/bDTw0LufSmH/GxTjEdpHEO+bVKFTwdrcGa/9XlKQ==",
      "dev": true,
      "dependencies": {
        "type-fest": "^2.5.1"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/new-github-release-url/node_modules/type-fest": {
      "version": "2.19.0",
      "resolved": "https://registry.npmmirror.com/type-fest/-/type-fest-2.19.0.tgz",
      "integrity": "sha512-RAH822pAdBgcNMAfWnCBU3CFZcfZ/i1eZjwFU/dsLKumyuuP3niueg2UAukXYF0E2AAoc82ZSSf9J0WQBinzHA==",
      "dev": true,
      "engines": {
        "node": ">=12.20"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/node-forge": {
      "version": "1.3.1",
      "resolved": "https://registry.npmmirror.com/node-forge/-/node-forge-1.3.1.tgz",
      "integrity": "sha512-dPEtOeMvF9VMcYV/1Wb8CPoVAXtp6MKMlcbAt4ddqmGqUJ6fQZFXkNZNkNlfevtNkGtaSoXf/vNNNSvgrdXwtA==",
      "engines": {
        "node": ">= 6.13.0"
      }
    },
    "node_modules/node-releases": {
      "version": "2.0.18",
      "resolved": "https://registry.npmmirror.com/node-releases/-/node-releases-2.0.18.tgz",
      "integrity": "sha512-d9VeXT4SJ7ZeOqGX6R5EM022wpL+eWPooLI+5UpWn2jCT1aosUQEhQP214x33Wkwx3JQMvIm+tIoVOdodFS40g==",
      "dev": true
    },
    "node_modules/normalize-range": {
      "version": "0.1.2",
      "resolved": "https://registry.npmmirror.com/normalize-range/-/normalize-range-0.1.2.tgz",
      "integrity": "sha512-bdok/XvKII3nUpklnV6P2hxtMNrCboOjAcyBuQnWEhO665FwrSNRxU+AqpsyvO6LgGYPspN+lu5CLtw4jPRKNA==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/normalize-url": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/normalize-url/-/normalize-url-2.0.1.tgz",
      "integrity": "sha512-D6MUW4K/VzoJ4rJ01JFKxDrtY1v9wrgzCX5f2qj/lzH1m/lW6MhUZFKerVsnyjOhOsYzI9Kqqak+10l4LvLpMw==",
      "dependencies": {
        "prepend-http": "^2.0.0",
        "query-string": "^5.0.1",
        "sort-keys": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/npm-conf": {
      "version": "1.1.3",
      "resolved": "https://registry.npmmirror.com/npm-conf/-/npm-conf-1.1.3.tgz",
      "integrity": "sha512-Yic4bZHJOt9RCFbRP3GgpqhScOY4HH3V2P8yBj6CeYq118Qr+BLXqT2JvpJ00mryLESpgOxf5XlFv4ZjXxLScw==",
      "dependencies": {
        "config-chain": "^1.1.11",
        "pify": "^3.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/npm-run-path": {
      "version": "5.3.0",
      "resolved": "https://registry.npmmirror.com/npm-run-path/-/npm-run-path-5.3.0.tgz",
      "integrity": "sha512-ppwTtiJZq0O/ai0z7yfudtBpWIoxM8yE6nHi1X47eFR2EWORqfbu6CnPlNsjeN683eT0qG6H/Pyf9fCcvjnnnQ==",
      "dev": true,
      "dependencies": {
        "path-key": "^4.0.0"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/npm-run-path/node_modules/path-key": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/path-key/-/path-key-4.0.0.tgz",
      "integrity": "sha512-haREypq7xkM7ErfgIyA0z+Bj4AGKlMSdlQE2jvJo6huWD1EdkKYV+G/T4nq0YEF2vgTT8kqMFKo1uHn950r4SQ==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/nth-check": {
      "version": "2.1.1",
      "resolved": "https://registry.npmmirror.com/nth-check/-/nth-check-2.1.1.tgz",
      "integrity": "sha512-lqjrjmaOoAnWfMmBPL+XNnynZh2+swxiX3WUE0s4yEHI6m+AwrK2UZOimIRl3X/4QctVqS8AiZjFqyOGrMXb/w==",
      "dev": true,
      "dependencies": {
        "boolbase": "^1.0.0"
      },
      "funding": {
        "url": "https://github.com/fb55/nth-check?sponsor=1"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmmirror.com/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmmirror.com/once/-/once-1.4.0.tgz",
      "integrity": "sha512-lNaJgI+2Q5URQBkccEKHTQOPaXdUxnZZElQTZY0MFUAuaEqe1E+Nyvgdz/aIyNi6Z9MzO5dv1H8n58/GELp3+w==",
      "dependencies": {
        "wrappy": "1"
      }
    },
    "node_modules/onetime": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/onetime/-/onetime-7.0.0.tgz",
      "integrity": "sha512-VXJjc87FScF88uafS3JllDgvAm+c/Slfz06lorj2uAY34rlUu0Nt+v8wreiImcrgAjjIHp1rXpTDlLOGw29WwQ==",
      "dependencies": {
        "mimic-function": "^5.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/open": {
      "version": "10.1.0",
      "resolved": "https://registry.npmmirror.com/open/-/open-10.1.0.tgz",
      "integrity": "sha512-mnkeQ1qP5Ue2wd+aivTD3NHd/lZ96Lu0jgf0pwktLPtx6cTZiH7tyeGRRHs0zX0rbrahXPnXlUnbeXyaBBuIaw==",
      "dev": true,
      "dependencies": {
        "default-browser": "^5.2.1",
        "define-lazy-prop": "^3.0.0",
        "is-inside-container": "^1.0.0",
        "is-wsl": "^3.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/ora": {
      "version": "8.1.1",
      "resolved": "https://registry.npmmirror.com/ora/-/ora-8.1.1.tgz",
      "integrity": "sha512-YWielGi1XzG1UTvOaCFaNgEnuhZVMSHYkW/FQ7UX8O26PtlpdM84c0f7wLPlkvx2RfiQmnzd61d/MGxmpQeJPw==",
      "dependencies": {
        "chalk": "^5.3.0",
        "cli-cursor": "^5.0.0",
        "cli-spinners": "^2.9.2",
        "is-interactive": "^2.0.0",
        "is-unicode-supported": "^2.0.0",
        "log-symbols": "^6.0.0",
        "stdin-discarder": "^0.2.2",
        "string-width": "^7.2.0",
        "strip-ansi": "^7.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/os-name": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/os-name/-/os-name-5.1.0.tgz",
      "integrity": "sha512-YEIoAnM6zFmzw3PQ201gCVCIWbXNyKObGlVvpAVvraAeOHnlYVKFssbA/riRX5R40WA6kKrZ7Dr7dWzO3nKSeQ==",
      "dev": true,
      "dependencies": {
        "macos-release": "^3.1.0",
        "windows-release": "^5.0.1"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/os-tmpdir": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/os-tmpdir/-/os-tmpdir-1.0.2.tgz",
      "integrity": "sha512-D2FR03Vir7FIu45XBY20mTb+/ZSWB00sjU9jdQXt83gDrI4Ztz5Fs7/yy74g2N5SVQY4xY1qDr4rNddwYRVX0g==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/p-cancelable": {
      "version": "0.4.1",
      "resolved": "https://registry.npmmirror.com/p-cancelable/-/p-cancelable-0.4.1.tgz",
      "integrity": "sha512-HNa1A8LvB1kie7cERyy21VNeHb2CWJJYqyyC2o3klWFfMGlFmWv2Z7sFgZH8ZiaYL95ydToKTFVXgMV/Os0bBQ==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/p-event": {
      "version": "2.3.1",
      "resolved": "https://registry.npmmirror.com/p-event/-/p-event-2.3.1.tgz",
      "integrity": "sha512-NQCqOFhbpVTMX4qMe8PF8lbGtzZ+LCiN7pcNrb/413Na7+TRoe1xkKUzuWa/YEJdGQ0FvKtj35EEbDoVPO2kbA==",
      "dependencies": {
        "p-timeout": "^2.0.1"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/p-finally": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/p-finally/-/p-finally-1.0.0.tgz",
      "integrity": "sha512-LICb2p9CB7FS+0eR1oqWnHhp0FljGLZCWBE9aix0Uye9W8LTQPwMTYVGWQWIw9RdQiDg4+epXQODwIYJtSJaow==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/p-is-promise": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/p-is-promise/-/p-is-promise-1.1.0.tgz",
      "integrity": "sha512-zL7VE4JVS2IFSkR2GQKDSPEVxkoH43/p7oEnwpdCndKYJO0HVeRB7fA8TJwuLOTBREtK0ea8eHaxdwcpob5dmg==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/p-timeout": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/p-timeout/-/p-timeout-2.0.1.tgz",
      "integrity": "sha512-88em58dDVB/KzPEx1X0N3LwFfYZPyDc4B6eF38M1rk9VTZMbxXXgjugz8mmwpS9Ox4BDZ+t6t3QP5+/gazweIA==",
      "dependencies": {
        "p-finally": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pac-proxy-agent": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/pac-proxy-agent/-/pac-proxy-agent-7.0.2.tgz",
      "integrity": "sha512-BFi3vZnO9X5Qt6NRz7ZOaPja3ic0PhlsmCRYLOpN11+mWBCR6XJDqW5RF3j8jm4WGGQZtBA+bTfxYzeKW73eHg==",
      "dev": true,
      "dependencies": {
        "@tootallnate/quickjs-emscripten": "^0.23.0",
        "agent-base": "^7.0.2",
        "debug": "^4.3.4",
        "get-uri": "^6.0.1",
        "http-proxy-agent": "^7.0.0",
        "https-proxy-agent": "^7.0.5",
        "pac-resolver": "^7.0.1",
        "socks-proxy-agent": "^8.0.4"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/pac-resolver": {
      "version": "7.0.1",
      "resolved": "https://registry.npmmirror.com/pac-resolver/-/pac-resolver-7.0.1.tgz",
      "integrity": "sha512-5NPgf87AT2STgwa2ntRMr45jTKrYBGkVU36yT0ig/n/GMAa3oPqhZfIQ2kMEimReg0+t9kZViDVZ83qfVUlckg==",
      "dev": true,
      "dependencies": {
        "degenerator": "^5.0.0",
        "netmask": "^2.0.2"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/package-json": {
      "version": "10.0.1",
      "resolved": "https://registry.npmmirror.com/package-json/-/package-json-10.0.1.tgz",
      "integrity": "sha512-ua1L4OgXSBdsu1FPb7F3tYH0F48a6kxvod4pLUlGY9COeJAJQNX/sNH2IiEmsxw7lqYiAwrdHMjz1FctOsyDQg==",
      "dev": true,
      "dependencies": {
        "ky": "^1.2.0",
        "registry-auth-token": "^5.0.2",
        "registry-url": "^6.0.1",
        "semver": "^7.6.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/package-json-from-dist": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/package-json-from-dist/-/package-json-from-dist-1.0.1.tgz",
      "integrity": "sha512-UEZIS3/by4OC8vL3P2dTXRETpebLI2NiI5vIrjaD/5UtrkFX/tNbwjTSRAGC/+7CAo2pIcBaRgWmcBBHcsaCIw=="
    },
    "node_modules/parent-module": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/parent-module/-/parent-module-1.0.1.tgz",
      "integrity": "sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==",
      "dev": true,
      "dependencies": {
        "callsites": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/parse-json": {
      "version": "5.2.0",
      "resolved": "https://registry.npmmirror.com/parse-json/-/parse-json-5.2.0.tgz",
      "integrity": "sha512-ayCKvm/phCGxOkYRSCM82iDwct8/EonSEgCSxWxD7ve6jHggsFl4fZVQBPRNgQoKiuV/odhFrGzQXZwbifC8Rg==",
      "dev": true,
      "dependencies": {
        "@babel/code-frame": "^7.0.0",
        "error-ex": "^1.3.1",
        "json-parse-even-better-errors": "^2.3.0",
        "lines-and-columns": "^1.1.6"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/parse-path": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/parse-path/-/parse-path-7.0.0.tgz",
      "integrity": "sha512-Euf9GG8WT9CdqwuWJGdf3RkUcTBArppHABkO7Lm8IzRQp0e2r/kkFnmhu4TSK30Wcu5rVAZLmfPKSBBi9tWFog==",
      "dev": true,
      "dependencies": {
        "protocols": "^2.0.0"
      }
    },
    "node_modules/parse-url": {
      "version": "8.1.0",
      "resolved": "https://registry.npmmirror.com/parse-url/-/parse-url-8.1.0.tgz",
      "integrity": "sha512-xDvOoLU5XRrcOZvnI6b8zA6n9O9ejNk/GExuz1yBuWUGn9KA97GI6HTs6u02wKara1CeVmZhH+0TZFdWScR89w==",
      "dev": true,
      "dependencies": {
        "parse-path": "^7.0.0"
      }
    },
    "node_modules/path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha512-AVbw3UJ2e9bq64vSaS9Am0fje1Pa8pbGqTTsmXfaIiMpnr5DlDhfJOuLj9Sf95ZPVDAUerDfEk88MPmPe7UCQg==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmmirror.com/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-parse": {
      "version": "1.0.7",
      "resolved": "https://registry.npmmirror.com/path-parse/-/path-parse-1.0.7.tgz",
      "integrity": "sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==",
      "dev": true
    },
    "node_modules/path-scurry": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/path-scurry/-/path-scurry-2.0.0.tgz",
      "integrity": "sha512-ypGJsmGtdXUOeM5u93TyeIEfEhM6s+ljAhrk5vAvSx8uyY/02OvrZnA0YNGUrPXfpJMgI1ODd3nwz8Npx4O4cg==",
      "dependencies": {
        "lru-cache": "^11.0.0",
        "minipass": "^7.1.2"
      },
      "engines": {
        "node": "20 || >=22"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/path-scurry/node_modules/lru-cache": {
      "version": "11.0.2",
      "resolved": "https://registry.npmmirror.com/lru-cache/-/lru-cache-11.0.2.tgz",
      "integrity": "sha512-123qHRfJBmo2jXDbo/a5YOQrJoHF/GNQTLzQ5+IdK5pWpceK17yRc6ozlWd25FxvGKQbIUs91fDFkXmDHTKcyA==",
      "engines": {
        "node": "20 || >=22"
      }
    },
    "node_modules/path-type": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/path-type/-/path-type-4.0.0.tgz",
      "integrity": "sha512-gDKb8aZMDeD/tZWs9P6+q0J9Mwkdl6xMV8TjnGP3qJVJ06bdMgkbBlLU8IdfOsIsFz2BW1rNVT3XuNEl8zPAvw==",
      "dev": true,
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/pathe": {
      "version": "1.1.2",
      "resolved": "https://registry.npmmirror.com/pathe/-/pathe-1.1.2.tgz",
      "integrity": "sha512-whLdWMYL2TwI08hn8/ZqAbrVemu0LNaNNJZX73O6qaIdCTfXutsLhMkjdENX0qhsQ9uIimo4/aQOmXkoon2nDQ==",
      "dev": true
    },
    "node_modules/pend": {
      "version": "1.2.0",
      "resolved": "https://registry.npmmirror.com/pend/-/pend-1.2.0.tgz",
      "integrity": "sha512-F3asv42UuXchdzt+xXqfW1OGlVBe+mxa2mqI0pg5yAHZPvFmY3Y6drSf/GQ1A86WgWEN9Kzh/WrgKa6iGcHXLg=="
    },
    "node_modules/picocolors": {
      "version": "1.1.1",
      "resolved": "https://registry.npmmirror.com/picocolors/-/picocolors-1.1.1.tgz",
      "integrity": "sha512-xceH2snhtb5M9liqDsmEw56le376mTZkEX/jEb/RxNFyegNul7eNslCXP9FDj/Lcu0X8KEyMceP2ntpaHrDEVA==",
      "dev": true
    },
    "node_modules/picomatch": {
      "version": "4.0.2",
      "resolved": "https://registry.npmmirror.com/picomatch/-/picomatch-4.0.2.tgz",
      "integrity": "sha512-M7BAV6Rlcy5u+m6oPhAPFgJTzAioX/6B0DxyvDlo9l8+T3nLKbrczg2WLUyzd45L8RqfUMyGPzekbMvX2Ldkwg==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/jonschlinkert"
      }
    },
    "node_modules/pify": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/pify/-/pify-3.0.0.tgz",
      "integrity": "sha512-C3FsVNH1udSEX48gGX1xfvwTWfsYWj5U+8/uK15BGzIGrKoUpghX8hWZwa/OFnakBiiVNmBvemTJR5mcy7iPcg==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pinkie": {
      "version": "2.0.4",
      "resolved": "https://registry.npmmirror.com/pinkie/-/pinkie-2.0.4.tgz",
      "integrity": "sha512-MnUuEycAemtSaeFSjXKW/aroV7akBbY+Sv+RkyqFjgAe73F+MR0TBWKBRDkmfWq/HiFmdavfZ1G7h4SPZXaCSg==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pinkie-promise": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/pinkie-promise/-/pinkie-promise-2.0.1.tgz",
      "integrity": "sha512-0Gni6D4UcLTbv9c57DfxDGdr41XfgUjqWZu492f0cIGr16zDU06BWP/RAEvOuo7CQ0CNjHaLlM59YJJFm3NWlw==",
      "dependencies": {
        "pinkie": "^2.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pkg-types": {
      "version": "1.2.1",
      "resolved": "https://registry.npmmirror.com/pkg-types/-/pkg-types-1.2.1.tgz",
      "integrity": "sha512-sQoqa8alT3nHjGuTjuKgOnvjo4cljkufdtLMnO2LBP/wRwuDlo1tkaEdMxCRhyGRPacv/ztlZgDPm2b7FAmEvw==",
      "dev": true,
      "dependencies": {
        "confbox": "^0.1.8",
        "mlly": "^1.7.2",
        "pathe": "^1.1.2"
      }
    },
    "node_modules/postcss": {
      "version": "8.4.47",
      "resolved": "https://registry.npmmirror.com/postcss/-/postcss-8.4.47.tgz",
      "integrity": "sha512-56rxCq7G/XfB4EkXq9Egn5GCqugWvDFjafDOThIdMBsI15iqPqR5r15TfSr1YPYeEI19YeaXMCbY6u88Y76GLQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/postcss"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "dependencies": {
        "nanoid": "^3.3.7",
        "picocolors": "^1.1.0",
        "source-map-js": "^1.2.1"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      }
    },
    "node_modules/postcss-calc": {
      "version": "10.0.2",
      "resolved": "https://registry.npmmirror.com/postcss-calc/-/postcss-calc-10.0.2.tgz",
      "integrity": "sha512-DT/Wwm6fCKgpYVI7ZEWuPJ4az8hiEHtCUeYjZXqU7Ou4QqYh1Df2yCQ7Ca6N7xqKPFkxN3fhf+u9KSoOCJNAjg==",
      "dev": true,
      "dependencies": {
        "postcss-selector-parser": "^6.1.2",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12 || ^20.9 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.38"
      }
    },
    "node_modules/postcss-colormin": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/postcss-colormin/-/postcss-colormin-7.0.2.tgz",
      "integrity": "sha512-YntRXNngcvEvDbEjTdRWGU606eZvB5prmHG4BF0yLmVpamXbpsRJzevyy6MZVyuecgzI2AWAlvFi8DAeCqwpvA==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "caniuse-api": "^3.0.0",
        "colord": "^2.9.3",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-convert-values": {
      "version": "7.0.4",
      "resolved": "https://registry.npmmirror.com/postcss-convert-values/-/postcss-convert-values-7.0.4.tgz",
      "integrity": "sha512-e2LSXPqEHVW6aoGbjV9RsSSNDO3A0rZLCBxN24zvxF25WknMPpX8Dm9UxxThyEbaytzggRuZxaGXqaOhxQ514Q==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-discard-comments": {
      "version": "7.0.3",
      "resolved": "https://registry.npmmirror.com/postcss-discard-comments/-/postcss-discard-comments-7.0.3.tgz",
      "integrity": "sha512-q6fjd4WU4afNhWOA2WltHgCbkRhZPgQe7cXF74fuVB/ge4QbM9HEaOIzGSiMvM+g/cOsNAUGdf2JDzqA2F8iLA==",
      "dev": true,
      "dependencies": {
        "postcss-selector-parser": "^6.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-discard-duplicates": {
      "version": "7.0.1",
      "resolved": "https://registry.npmmirror.com/postcss-discard-duplicates/-/postcss-discard-duplicates-7.0.1.tgz",
      "integrity": "sha512-oZA+v8Jkpu1ct/xbbrntHRsfLGuzoP+cpt0nJe5ED2FQF8n8bJtn7Bo28jSmBYwqgqnqkuSXJfSUEE7if4nClQ==",
      "dev": true,
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-discard-empty": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-discard-empty/-/postcss-discard-empty-7.0.0.tgz",
      "integrity": "sha512-e+QzoReTZ8IAwhnSdp/++7gBZ/F+nBq9y6PomfwORfP7q9nBpK5AMP64kOt0bA+lShBFbBDcgpJ3X4etHg4lzA==",
      "dev": true,
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-discard-overridden": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-discard-overridden/-/postcss-discard-overridden-7.0.0.tgz",
      "integrity": "sha512-GmNAzx88u3k2+sBTZrJSDauR0ccpE24omTQCVmaTTZFz1du6AasspjaUPMJ2ud4RslZpoFKyf+6MSPETLojc6w==",
      "dev": true,
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-merge-longhand": {
      "version": "7.0.4",
      "resolved": "https://registry.npmmirror.com/postcss-merge-longhand/-/postcss-merge-longhand-7.0.4.tgz",
      "integrity": "sha512-zer1KoZA54Q8RVHKOY5vMke0cCdNxMP3KBfDerjH/BYHh4nCIh+1Yy0t1pAEQF18ac/4z3OFclO+ZVH8azjR4A==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0",
        "stylehacks": "^7.0.4"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-merge-rules": {
      "version": "7.0.4",
      "resolved": "https://registry.npmmirror.com/postcss-merge-rules/-/postcss-merge-rules-7.0.4.tgz",
      "integrity": "sha512-ZsaamiMVu7uBYsIdGtKJ64PkcQt6Pcpep/uO90EpLS3dxJi6OXamIobTYcImyXGoW0Wpugh7DSD3XzxZS9JCPg==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "caniuse-api": "^3.0.0",
        "cssnano-utils": "^5.0.0",
        "postcss-selector-parser": "^6.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-minify-font-values": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-minify-font-values/-/postcss-minify-font-values-7.0.0.tgz",
      "integrity": "sha512-2ckkZtgT0zG8SMc5aoNwtm5234eUx1GGFJKf2b1bSp8UflqaeFzR50lid4PfqVI9NtGqJ2J4Y7fwvnP/u1cQog==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-minify-gradients": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-minify-gradients/-/postcss-minify-gradients-7.0.0.tgz",
      "integrity": "sha512-pdUIIdj/C93ryCHew0UgBnL2DtUS3hfFa5XtERrs4x+hmpMYGhbzo6l/Ir5de41O0GaKVpK1ZbDNXSY6GkXvtg==",
      "dev": true,
      "dependencies": {
        "colord": "^2.9.3",
        "cssnano-utils": "^5.0.0",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-minify-params": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/postcss-minify-params/-/postcss-minify-params-7.0.2.tgz",
      "integrity": "sha512-nyqVLu4MFl9df32zTsdcLqCFfE/z2+f8GE1KHPxWOAmegSo6lpV2GNy5XQvrzwbLmiU7d+fYay4cwto1oNdAaQ==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "cssnano-utils": "^5.0.0",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-minify-selectors": {
      "version": "7.0.4",
      "resolved": "https://registry.npmmirror.com/postcss-minify-selectors/-/postcss-minify-selectors-7.0.4.tgz",
      "integrity": "sha512-JG55VADcNb4xFCf75hXkzc1rNeURhlo7ugf6JjiiKRfMsKlDzN9CXHZDyiG6x/zGchpjQS+UAgb1d4nqXqOpmA==",
      "dev": true,
      "dependencies": {
        "cssesc": "^3.0.0",
        "postcss-selector-parser": "^6.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-nested": {
      "version": "6.2.0",
      "resolved": "https://registry.npmmirror.com/postcss-nested/-/postcss-nested-6.2.0.tgz",
      "integrity": "sha512-HQbt28KulC5AJzG+cZtj9kvKB93CFCdLvog1WFLf1D+xmMvPGlBstkpTEZfK5+AN9hfJocyBFCNiqyS48bpgzQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "dependencies": {
        "postcss-selector-parser": "^6.1.1"
      },
      "engines": {
        "node": ">=12.0"
      },
      "peerDependencies": {
        "postcss": "^8.2.14"
      }
    },
    "node_modules/postcss-normalize-charset": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-charset/-/postcss-normalize-charset-7.0.0.tgz",
      "integrity": "sha512-ABisNUXMeZeDNzCQxPxBCkXexvBrUHV+p7/BXOY+ulxkcjUZO0cp8ekGBwvIh2LbCwnWbyMPNJVtBSdyhM2zYQ==",
      "dev": true,
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-display-values": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-display-values/-/postcss-normalize-display-values-7.0.0.tgz",
      "integrity": "sha512-lnFZzNPeDf5uGMPYgGOw7v0BfB45+irSRz9gHQStdkkhiM0gTfvWkWB5BMxpn0OqgOQuZG/mRlZyJxp0EImr2Q==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-positions": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-positions/-/postcss-normalize-positions-7.0.0.tgz",
      "integrity": "sha512-I0yt8wX529UKIGs2y/9Ybs2CelSvItfmvg/DBIjTnoUSrPxSV7Z0yZ8ShSVtKNaV/wAY+m7bgtyVQLhB00A1NQ==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-repeat-style": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-repeat-style/-/postcss-normalize-repeat-style-7.0.0.tgz",
      "integrity": "sha512-o3uSGYH+2q30ieM3ppu9GTjSXIzOrRdCUn8UOMGNw7Af61bmurHTWI87hRybrP6xDHvOe5WlAj3XzN6vEO8jLw==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-string": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-string/-/postcss-normalize-string-7.0.0.tgz",
      "integrity": "sha512-w/qzL212DFVOpMy3UGyxrND+Kb0fvCiBBujiaONIihq7VvtC7bswjWgKQU/w4VcRyDD8gpfqUiBQ4DUOwEJ6Qg==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-timing-functions": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-timing-functions/-/postcss-normalize-timing-functions-7.0.0.tgz",
      "integrity": "sha512-tNgw3YV0LYoRwg43N3lTe3AEWZ66W7Dh7lVEpJbHoKOuHc1sLrzMLMFjP8SNULHaykzsonUEDbKedv8C+7ej6g==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-unicode": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-unicode/-/postcss-normalize-unicode-7.0.2.tgz",
      "integrity": "sha512-ztisabK5C/+ZWBdYC+Y9JCkp3M9qBv/XFvDtSw0d/XwfT3UaKeW/YTm/MD/QrPNxuecia46vkfEhewjwcYFjkg==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-url": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-url/-/postcss-normalize-url-7.0.0.tgz",
      "integrity": "sha512-+d7+PpE+jyPX1hDQZYG+NaFD+Nd2ris6r8fPTBAjE8z/U41n/bib3vze8x7rKs5H1uEw5ppe9IojewouHk0klQ==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-normalize-whitespace": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-normalize-whitespace/-/postcss-normalize-whitespace-7.0.0.tgz",
      "integrity": "sha512-37/toN4wwZErqohedXYqWgvcHUGlT8O/m2jVkAfAe9Bd4MzRqlBmXrJRePH0e9Wgnz2X7KymTgTOaaFizQe3AQ==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-ordered-values": {
      "version": "7.0.1",
      "resolved": "https://registry.npmmirror.com/postcss-ordered-values/-/postcss-ordered-values-7.0.1.tgz",
      "integrity": "sha512-irWScWRL6nRzYmBOXReIKch75RRhNS86UPUAxXdmW/l0FcAsg0lvAXQCby/1lymxn/o0gVa6Rv/0f03eJOwHxw==",
      "dev": true,
      "dependencies": {
        "cssnano-utils": "^5.0.0",
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-reduce-initial": {
      "version": "7.0.2",
      "resolved": "https://registry.npmmirror.com/postcss-reduce-initial/-/postcss-reduce-initial-7.0.2.tgz",
      "integrity": "sha512-pOnu9zqQww7dEKf62Nuju6JgsW2V0KRNBHxeKohU+JkHd/GAH5uvoObqFLqkeB2n20mr6yrlWDvo5UBU5GnkfA==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "caniuse-api": "^3.0.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-reduce-transforms": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/postcss-reduce-transforms/-/postcss-reduce-transforms-7.0.0.tgz",
      "integrity": "sha512-pnt1HKKZ07/idH8cpATX/ujMbtOGhUfE+m8gbqwJE05aTaNw8gbo34a2e3if0xc0dlu75sUOiqvwCGY3fzOHew==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-selector-parser": {
      "version": "6.1.2",
      "resolved": "https://registry.npmmirror.com/postcss-selector-parser/-/postcss-selector-parser-6.1.2.tgz",
      "integrity": "sha512-Q8qQfPiZ+THO/3ZrOrO0cJJKfpYCagtMUkXbnEfmgUjwXg6z/WBeOyS9APBBPCTSiDV+s4SwQGu8yFsiMRIudg==",
      "dev": true,
      "dependencies": {
        "cssesc": "^3.0.0",
        "util-deprecate": "^1.0.2"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/postcss-svgo": {
      "version": "7.0.1",
      "resolved": "https://registry.npmmirror.com/postcss-svgo/-/postcss-svgo-7.0.1.tgz",
      "integrity": "sha512-0WBUlSL4lhD9rA5k1e5D8EN5wCEyZD6HJk0jIvRxl+FDVOMlJ7DePHYWGGVc5QRqrJ3/06FTXM0bxjmJpmTPSA==",
      "dev": true,
      "dependencies": {
        "postcss-value-parser": "^4.2.0",
        "svgo": "^3.3.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >= 18"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-unique-selectors": {
      "version": "7.0.3",
      "resolved": "https://registry.npmmirror.com/postcss-unique-selectors/-/postcss-unique-selectors-7.0.3.tgz",
      "integrity": "sha512-J+58u5Ic5T1QjP/LDV9g3Cx4CNOgB5vz+kM6+OxHHhFACdcDeKhBXjQmB7fnIZM12YSTvsL0Opwco83DmacW2g==",
      "dev": true,
      "dependencies": {
        "postcss-selector-parser": "^6.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/postcss-value-parser": {
      "version": "4.2.0",
      "resolved": "https://registry.npmmirror.com/postcss-value-parser/-/postcss-value-parser-4.2.0.tgz",
      "integrity": "sha512-1NNCs6uurfkVbeXG4S8JFT9t19m45ICnif8zWLd5oPSZ50QnwMfK+H3jv408d4jw/7Bttv5axS5IiHoLaVNHeQ==",
      "dev": true
    },
    "node_modules/prepend-http": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/prepend-http/-/prepend-http-2.0.0.tgz",
      "integrity": "sha512-ravE6m9Atw9Z/jjttRUZ+clIXogdghyZAuWJ3qEzjT+jI/dL1ifAqhZeC5VHzQp1MSt1+jxKkFNemj/iO7tVUA==",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/pretty-bytes": {
      "version": "6.1.1",
      "resolved": "https://registry.npmmirror.com/pretty-bytes/-/pretty-bytes-6.1.1.tgz",
      "integrity": "sha512-mQUvGU6aUFQ+rNvTIAcZuWGRT9a6f6Yrg9bHs4ImKF+HZCEK+plBvnAZYSIQztknZF2qnzNtr6F8s0+IuptdlQ==",
      "dev": true,
      "engines": {
        "node": "^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/process-nextick-args": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/process-nextick-args/-/process-nextick-args-2.0.1.tgz",
      "integrity": "sha512-3ouUOpQhtgrbOa17J7+uxOTpITYWaGP7/AhoR3+A+/1e9skrzelGi/dXzEYyvbxubEF6Wn2ypscTKiKJFFn1ag=="
    },
    "node_modules/prompts": {
      "version": "2.4.2",
      "resolved": "https://registry.npmmirror.com/prompts/-/prompts-2.4.2.tgz",
      "integrity": "sha512-NxNv/kLguCA7p3jE8oL2aEBsrJWgAakBpgmgK6lpPWV+WuOmY6r2/zbAVnP+T8bQlA0nzHXSJSJW0Hq7ylaD2Q==",
      "dependencies": {
        "kleur": "^3.0.3",
        "sisteransi": "^1.0.5"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/proto-list": {
      "version": "1.2.4",
      "resolved": "https://registry.npmmirror.com/proto-list/-/proto-list-1.2.4.tgz",
      "integrity": "sha512-vtK/94akxsTMhe0/cbfpR+syPuszcuwhqVjJq26CuNDgFGj682oRBXOP5MJpv2r7JtE8MsiepGIqvvOTBwn2vA=="
    },
    "node_modules/protocols": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/protocols/-/protocols-2.0.1.tgz",
      "integrity": "sha512-/XJ368cyBJ7fzLMwLKv1e4vLxOju2MNAIokcr7meSaNcVbWz/CPcW22cP04mwxOErdA5mwjA8Q6w/cdAQxVn7Q==",
      "dev": true
    },
    "node_modules/proxy-agent": {
      "version": "6.4.0",
      "resolved": "https://registry.npmmirror.com/proxy-agent/-/proxy-agent-6.4.0.tgz",
      "integrity": "sha512-u0piLU+nCOHMgGjRbimiXmA9kM/L9EHh3zL81xCdp7m+Y2pHIsnmbdDoEDoAz5geaonNR6q6+yOPQs6n4T6sBQ==",
      "dev": true,
      "dependencies": {
        "agent-base": "^7.0.2",
        "debug": "^4.3.4",
        "http-proxy-agent": "^7.0.1",
        "https-proxy-agent": "^7.0.3",
        "lru-cache": "^7.14.1",
        "pac-proxy-agent": "^7.0.1",
        "proxy-from-env": "^1.1.0",
        "socks-proxy-agent": "^8.0.2"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/proxy-agent/node_modules/lru-cache": {
      "version": "7.18.3",
      "resolved": "https://registry.npmmirror.com/lru-cache/-/lru-cache-7.18.3.tgz",
      "integrity": "sha512-jumlc0BIUrS3qJGgIkWZsyfAM7NCWiBcCDhnd+3NNM5KbBmLTgHVfWBcg6W+rLUsIpzpERPsvwUP7CckAQSOoA==",
      "dev": true,
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg=="
    },
    "node_modules/pupa": {
      "version": "3.1.0",
      "resolved": "https://registry.npmmirror.com/pupa/-/pupa-3.1.0.tgz",
      "integrity": "sha512-FLpr4flz5xZTSJxSeaheeMKN/EDzMdK7b8PTOC6a5PYFKTucWbdqjgqaEyH0shFiSJrVB1+Qqi4Tk19ccU6Aug==",
      "dev": true,
      "dependencies": {
        "escape-goat": "^4.0.0"
      },
      "engines": {
        "node": ">=12.20"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/query-string": {
      "version": "5.1.1",
      "resolved": "https://registry.npmmirror.com/query-string/-/query-string-5.1.1.tgz",
      "integrity": "sha512-gjWOsm2SoGlgLEdAGt7a6slVOk9mGiXmPFMqrEhLQ68rhQuBnpfs3+EmlvqKyxnCo9/PPlF+9MtY02S1aFg+Jw==",
      "dependencies": {
        "decode-uri-component": "^0.2.0",
        "object-assign": "^4.1.0",
        "strict-uri-encode": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/queue-microtask": {
      "version": "1.2.3",
      "resolved": "https://registry.npmmirror.com/queue-microtask/-/queue-microtask-1.2.3.tgz",
      "integrity": "sha512-NuaNSa6flKT5JaSYQzJok04JzTL1CA6aGhv5rfLW3PgqA+M2ChpZQnAC8h8i4ZFkBS8X5RqkDBHA7r4hej3K9A==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ]
    },
    "node_modules/rc": {
      "version": "1.2.8",
      "resolved": "https://registry.npmmirror.com/rc/-/rc-1.2.8.tgz",
      "integrity": "sha512-y3bGgqKj3QBdxLbLkomlohkvsA8gdAiUQlSBJnBhfn+BPxg4bc62d8TcBW15wavDfgexCgccckhcZvywyQYPOw==",
      "dev": true,
      "dependencies": {
        "deep-extend": "^0.6.0",
        "ini": "~1.3.0",
        "minimist": "^1.2.0",
        "strip-json-comments": "~2.0.1"
      },
      "bin": {
        "rc": "cli.js"
      }
    },
    "node_modules/readable-stream": {
      "version": "2.3.8",
      "resolved": "https://registry.npmmirror.com/readable-stream/-/readable-stream-2.3.8.tgz",
      "integrity": "sha512-8p0AUk4XODgIewSi0l8Epjs+EVnWiK7NoDIEGU0HhE7+ZyY8D1IMY7odu5lRrFXGg71L15KG8QrPmum45RTtdA==",
      "dependencies": {
        "core-util-is": "~1.0.0",
        "inherits": "~2.0.3",
        "isarray": "~1.0.0",
        "process-nextick-args": "~2.0.0",
        "safe-buffer": "~5.1.1",
        "string_decoder": "~1.1.1",
        "util-deprecate": "~1.0.1"
      }
    },
    "node_modules/readable-stream/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g=="
    },
    "node_modules/rechoir": {
      "version": "0.6.2",
      "resolved": "https://registry.npmmirror.com/rechoir/-/rechoir-0.6.2.tgz",
      "integrity": "sha512-HFM8rkZ+i3zrV+4LQjwQ0W+ez98pApMGM3HUrN04j3CqzPOzl9nmP15Y8YXNm8QHGv/eacOVEjqhmWpkRV0NAw==",
      "dev": true,
      "dependencies": {
        "resolve": "^1.1.6"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/registry-auth-token": {
      "version": "5.0.2",
      "resolved": "https://registry.npmmirror.com/registry-auth-token/-/registry-auth-token-5.0.2.tgz",
      "integrity": "sha512-o/3ikDxtXaA59BmZuZrJZDJv8NMDGSj+6j6XaeBmHw8eY1i1qd9+6H+LjVvQXx3HN6aRCGa1cUdJ9RaJZUugnQ==",
      "dev": true,
      "dependencies": {
        "@pnpm/npm-conf": "^2.1.0"
      },
      "engines": {
        "node": ">=14"
      }
    },
    "node_modules/registry-url": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/registry-url/-/registry-url-6.0.1.tgz",
      "integrity": "sha512-+crtS5QjFRqFCoQmvGduwYWEBng99ZvmFvF+cUJkGYF1L1BfU8C6Zp9T7f5vPAwyLkUExpvK+ANVZmGU49qi4Q==",
      "dev": true,
      "dependencies": {
        "rc": "1.2.8"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/release-it": {
      "version": "17.10.0",
      "resolved": "https://registry.npmmirror.com/release-it/-/release-it-17.10.0.tgz",
      "integrity": "sha512-00cXYEl7RFD5NnjXpwaH9JFjpwe8w3NcfUd4XPxrKQkszp1xppPo42zK9eSbxStKyPA5CVk2KmKPDPDiAKVJTA==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/webpro"
        },
        {
          "type": "opencollective",
          "url": "https://opencollective.com/webpro"
        }
      ],
      "dependencies": {
        "@iarna/toml": "2.2.5",
        "@octokit/rest": "20.1.1",
        "async-retry": "1.3.3",
        "chalk": "5.3.0",
        "ci-info": "^4.0.0",
        "cosmiconfig": "9.0.0",
        "execa": "8.0.0",
        "git-url-parse": "14.0.0",
        "globby": "14.0.2",
        "inquirer": "9.3.2",
        "issue-parser": "7.0.1",
        "lodash": "4.17.21",
        "mime-types": "2.1.35",
        "new-github-release-url": "2.0.0",
        "open": "10.1.0",
        "ora": "8.1.0",
        "os-name": "5.1.0",
        "proxy-agent": "6.4.0",
        "semver": "7.6.3",
        "shelljs": "0.8.5",
        "update-notifier": "7.3.1",
        "url-join": "5.0.0",
        "wildcard-match": "5.1.3",
        "yargs-parser": "21.1.1"
      },
      "bin": {
        "release-it": "bin/release-it.js"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || ^22.0.0"
      }
    },
    "node_modules/release-it/node_modules/globby": {
      "version": "14.0.2",
      "resolved": "https://registry.npmmirror.com/globby/-/globby-14.0.2.tgz",
      "integrity": "sha512-s3Fq41ZVh7vbbe2PN3nrW7yC7U7MFVc5c98/iTl9c2GawNMKx/J648KQRW6WKkuU8GIbbh2IXfIRQjOZnXcTnw==",
      "dev": true,
      "dependencies": {
        "@sindresorhus/merge-streams": "^2.1.0",
        "fast-glob": "^3.3.2",
        "ignore": "^5.2.4",
        "path-type": "^5.0.0",
        "slash": "^5.1.0",
        "unicorn-magic": "^0.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/release-it/node_modules/ora": {
      "version": "8.1.0",
      "resolved": "https://registry.npmmirror.com/ora/-/ora-8.1.0.tgz",
      "integrity": "sha512-GQEkNkH/GHOhPFXcqZs3IDahXEQcQxsSjEkK4KvEEST4t7eNzoMjxTzef+EZ+JluDEV+Raoi3WQ2CflnRdSVnQ==",
      "dev": true,
      "dependencies": {
        "chalk": "^5.3.0",
        "cli-cursor": "^5.0.0",
        "cli-spinners": "^2.9.2",
        "is-interactive": "^2.0.0",
        "is-unicode-supported": "^2.0.0",
        "log-symbols": "^6.0.0",
        "stdin-discarder": "^0.2.2",
        "string-width": "^7.2.0",
        "strip-ansi": "^7.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/release-it/node_modules/path-type": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/path-type/-/path-type-5.0.0.tgz",
      "integrity": "sha512-5HviZNaZcfqP95rwpv+1HDgUamezbqdSYTyzjTvwtJSnIH+3vnbmWsItli8OFEndS984VT55M3jduxZbX351gg==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/release-it/node_modules/slash": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/slash/-/slash-5.1.0.tgz",
      "integrity": "sha512-ZA6oR3T/pEyuqwMgAKT0/hAv8oAXckzbkmR0UkUosQ+Mc4RxGoJkRmwHgHufaenlyAgE1Mxgpdcrf75y6XcnDg==",
      "dev": true,
      "engines": {
        "node": ">=14.16"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/resolve": {
      "version": "1.22.8",
      "resolved": "https://registry.npmmirror.com/resolve/-/resolve-1.22.8.tgz",
      "integrity": "sha512-oKWePCxqpd6FlLvGV1VU0x7bkPmmCNolxzjMf4NczoDnQcIWrAF+cPtZn5i6n+RfD2d9i0tzpKnG6Yk168yIyw==",
      "dev": true,
      "dependencies": {
        "is-core-module": "^2.13.0",
        "path-parse": "^1.0.7",
        "supports-preserve-symlinks-flag": "^1.0.0"
      },
      "bin": {
        "resolve": "bin/resolve"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/resolve-from": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/resolve-from/-/resolve-from-4.0.0.tgz",
      "integrity": "sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==",
      "dev": true,
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/responselike": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/responselike/-/responselike-1.0.2.tgz",
      "integrity": "sha512-/Fpe5guzJk1gPqdJLJR5u7eG/gNY4nImjbRDaVWVMRhne55TCmj2i9Q+54PBRfatRC8v/rIiv9BN0pMd9OV5EQ==",
      "dependencies": {
        "lowercase-keys": "^1.0.0"
      }
    },
    "node_modules/restore-cursor": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/restore-cursor/-/restore-cursor-5.1.0.tgz",
      "integrity": "sha512-oMA2dcrw6u0YfxJQXm342bFKX/E4sG9rbTzO9ptUcR/e8A33cHuvStiYOwH7fszkZlZ1z/ta9AAoPk2F4qIOHA==",
      "dependencies": {
        "onetime": "^7.0.0",
        "signal-exit": "^4.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/retry": {
      "version": "0.13.1",
      "resolved": "https://registry.npmmirror.com/retry/-/retry-0.13.1.tgz",
      "integrity": "sha512-XQBQ3I8W1Cge0Seh+6gjj03LbmRFWuoszgK9ooCpwYIrhhoO80pfq4cUkU5DkknwfOfFteRwlZ56PYOGYyFWdg==",
      "dev": true,
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/reusify": {
      "version": "1.0.4",
      "resolved": "https://registry.npmmirror.com/reusify/-/reusify-1.0.4.tgz",
      "integrity": "sha512-U9nH88a3fc/ekCF1l0/UP1IosiuIjyTh7hBvXVMHYgVcfGvt897Xguj2UOLDeI5BG2m7/uwyaLVT6fbtCwTyzw==",
      "dev": true,
      "engines": {
        "iojs": ">=1.0.0",
        "node": ">=0.10.0"
      }
    },
    "node_modules/rimraf": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/rimraf/-/rimraf-6.0.1.tgz",
      "integrity": "sha512-9dkvaxAsk/xNXSJzMgFqqMCuFgt2+KsOFek3TMLfo8NCPfWpBmqwyNn5Y+NX56QUYfCtsyhF3ayiboEoUmJk/A==",
      "dependencies": {
        "glob": "^11.0.0",
        "package-json-from-dist": "^1.0.0"
      },
      "bin": {
        "rimraf": "dist/esm/bin.mjs"
      },
      "engines": {
        "node": "20 || >=22"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/rimraf/node_modules/glob": {
      "version": "11.0.0",
      "resolved": "https://registry.npmmirror.com/glob/-/glob-11.0.0.tgz",
      "integrity": "sha512-9UiX/Bl6J2yaBbxKoEBRm4Cipxgok8kQYcOPEhScPwebu2I0HoQOuYdIO6S3hLuWoZgpDpwQZMzTFxgpkyT76g==",
      "dependencies": {
        "foreground-child": "^3.1.0",
        "jackspeak": "^4.0.1",
        "minimatch": "^10.0.0",
        "minipass": "^7.1.2",
        "package-json-from-dist": "^1.0.0",
        "path-scurry": "^2.0.0"
      },
      "bin": {
        "glob": "dist/esm/bin.mjs"
      },
      "engines": {
        "node": "20 || >=22"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/rimraf/node_modules/minimatch": {
      "version": "10.0.1",
      "resolved": "https://registry.npmmirror.com/minimatch/-/minimatch-10.0.1.tgz",
      "integrity": "sha512-ethXTt3SGGR+95gudmqJ1eNhRO7eGEGIgYA9vnPatK4/etz2MEVDno5GMCibdMTuBMyElzIlgxMna3K94XDIDQ==",
      "dependencies": {
        "brace-expansion": "^2.0.1"
      },
      "engines": {
        "node": "20 || >=22"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/rollup": {
      "version": "3.29.5",
      "resolved": "https://registry.npmmirror.com/rollup/-/rollup-3.29.5.tgz",
      "integrity": "sha512-GVsDdsbJzzy4S/v3dqWPJ7EfvZJfCHiDqe80IyrF59LYuP+e6U1LJoUqeuqRbwAWoMNoXivMNeNAOf5E22VA1w==",
      "dev": true,
      "bin": {
        "rollup": "dist/bin/rollup"
      },
      "engines": {
        "node": ">=14.18.0",
        "npm": ">=8.0.0"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/rollup-plugin-dts": {
      "version": "6.1.1",
      "resolved": "https://registry.npmmirror.com/rollup-plugin-dts/-/rollup-plugin-dts-6.1.1.tgz",
      "integrity": "sha512-aSHRcJ6KG2IHIioYlvAOcEq6U99sVtqDDKVhnwt70rW6tsz3tv5OSjEiWcgzfsHdLyGXZ/3b/7b/+Za3Y6r1XA==",
      "dev": true,
      "dependencies": {
        "magic-string": "^0.30.10"
      },
      "engines": {
        "node": ">=16"
      },
      "funding": {
        "url": "https://github.com/sponsors/Swatinem"
      },
      "optionalDependencies": {
        "@babel/code-frame": "^7.24.2"
      },
      "peerDependencies": {
        "rollup": "^3.29.4 || ^4",
        "typescript": "^4.5 || ^5.0"
      }
    },
    "node_modules/run-applescript": {
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/run-applescript/-/run-applescript-7.0.0.tgz",
      "integrity": "sha512-9by4Ij99JUr/MCFBUkDKLWK3G9HVXmabKz9U5MlIAIuvuzkiOicRYs8XJLxX+xahD+mLiiCYDqF9dKAgtzKP1A==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/run-async": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/run-async/-/run-async-3.0.0.tgz",
      "integrity": "sha512-540WwVDOMxA6dN6We19EcT9sc3hkXPw5mzRNGM3FkdN/vtE9NFvj5lFAPNwUDmJjXidm3v7TC1cTE7t17Ulm1Q==",
      "dev": true,
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/run-parallel": {
      "version": "1.2.0",
      "resolved": "https://registry.npmmirror.com/run-parallel/-/run-parallel-1.2.0.tgz",
      "integrity": "sha512-5l4VyZR86LZ/lDxZTR6jqL8AFE2S0IFLMP26AbjsLVADxHdhB/c0GUsH+y39UfCi3dzz8OlQuPmnaJOMoDHQBA==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "dependencies": {
        "queue-microtask": "^1.2.2"
      }
    },
    "node_modules/rxjs": {
      "version": "7.8.1",
      "resolved": "https://registry.npmmirror.com/rxjs/-/rxjs-7.8.1.tgz",
      "integrity": "sha512-AA3TVj+0A2iuIoQkWEK/tqFjBq2j+6PO6Y0zJcvzLAFhEFIO3HL0vls9hWLncZbAAbK0mar7oZ4V079I/qPMxg==",
      "dev": true,
      "dependencies": {
        "tslib": "^2.1.0"
      }
    },
    "node_modules/safe-buffer": {
      "version": "5.2.1",
      "resolved": "https://registry.npmmirror.com/safe-buffer/-/safe-buffer-5.2.1.tgz",
      "integrity": "sha512-rp3So07KcdmmKbGvgaNxQSJr7bGVSVk5S9Eq1F+ppbRo70+YeaDxkw5Dd8NPN+GD6bjnYm2VuPuCXmpuYvmCXQ==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ]
    },
    "node_modules/safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmmirror.com/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg==",
      "dev": true
    },
    "node_modules/scule": {
      "version": "1.3.0",
      "resolved": "https://registry.npmmirror.com/scule/-/scule-1.3.0.tgz",
      "integrity": "sha512-6FtHJEvt+pVMIB9IBY+IcCJ6Z5f1iQnytgyfKMhDKgmzYG+TeH/wx1y3l27rshSbLiSanrR9ffZDrEsmjlQF2g==",
      "dev": true
    },
    "node_modules/seek-bzip": {
      "version": "1.0.6",
      "resolved": "https://registry.npmmirror.com/seek-bzip/-/seek-bzip-1.0.6.tgz",
      "integrity": "sha512-e1QtP3YL5tWww8uKaOCQ18UxIT2laNBXHjV/S2WYCiK4udiv8lkG89KRIoCjUagnAmCBurjF4zEVX2ByBbnCjQ==",
      "dependencies": {
        "commander": "^2.8.1"
      },
      "bin": {
        "seek-bunzip": "bin/seek-bunzip",
        "seek-table": "bin/seek-bzip-table"
      }
    },
    "node_modules/seek-bzip/node_modules/commander": {
      "version": "2.20.3",
      "resolved": "https://registry.npmmirror.com/commander/-/commander-2.20.3.tgz",
      "integrity": "sha512-GpVkmM8vF2vQUkj2LvZmD35JxeJOLCwJ9cUkugyk2nuhbv3+mJvpLYYt+0+USMxE+oj+ey/lJEnhZw75x/OMcQ=="
    },
    "node_modules/semver": {
      "version": "7.6.3",
      "resolved": "https://registry.npmmirror.com/semver/-/semver-7.6.3.tgz",
      "integrity": "sha512-oVekP1cKtI+CTDvHWYFUcMtsK/00wmAEfyqKfNdARm8u1wNVhSgaX7A8d4UuIlUI5e84iEwOhs7ZPYRmzU9U6A==",
      "dev": true,
      "bin": {
        "semver": "bin/semver.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/shebang-command": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/shebang-command/-/shebang-command-2.0.0.tgz",
      "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
      "dependencies": {
        "shebang-regex": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/shebang-regex": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/shebang-regex/-/shebang-regex-3.0.0.tgz",
      "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/shelljs": {
      "version": "0.8.5",
      "resolved": "https://registry.npmmirror.com/shelljs/-/shelljs-0.8.5.tgz",
      "integrity": "sha512-TiwcRcrkhHvbrZbnRcFYMLl30Dfov3HKqzp5tO5b4pt6G/SezKcYhmDg15zXVBswHmctSAQKznqNW2LO5tTDow==",
      "dev": true,
      "dependencies": {
        "glob": "^7.0.0",
        "interpret": "^1.0.0",
        "rechoir": "^0.6.2"
      },
      "bin": {
        "shjs": "bin/shjs"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/shelljs/node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmmirror.com/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dev": true,
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/shelljs/node_modules/glob": {
      "version": "7.2.3",
      "resolved": "https://registry.npmmirror.com/glob/-/glob-7.2.3.tgz",
      "integrity": "sha512-nFR0zLpU2YCaRxwoCJvL6UvCH2JFyFVIvwTLsIf21AuHlMskA1hhTdk+LlYJtOlYt9v6dvszD2BGRqBL+iQK9Q==",
      "deprecated": "Glob versions prior to v9 are no longer supported",
      "dev": true,
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.1.1",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      },
      "engines": {
        "node": "*"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/shelljs/node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmmirror.com/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dev": true,
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/signal-exit": {
      "version": "4.1.0",
      "resolved": "https://registry.npmmirror.com/signal-exit/-/signal-exit-4.1.0.tgz",
      "integrity": "sha512-bzyZ1e88w9O1iNJbKnOlvYTrWPDl46O1bG0D3XInv+9tkPrxrN8jUUTiFlDkkmKWgn1M6CfIA13SuGqOa9Korw==",
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/sisteransi": {
      "version": "1.0.5",
      "resolved": "https://registry.npmmirror.com/sisteransi/-/sisteransi-1.0.5.tgz",
      "integrity": "sha512-bLGGlR1QxBcynn2d5YmDX4MGjlZvy2MRBDRNHLJ8VI6l6+9FUiyTFNJ0IveOSP0bcXgVDPRcfGqA0pjaqUpfVg=="
    },
    "node_modules/slash": {
      "version": "4.0.0",
      "resolved": "https://registry.npmmirror.com/slash/-/slash-4.0.0.tgz",
      "integrity": "sha512-3dOsAHXXUkQTpOYcoAxLIorMTp4gIQr5IW3iVb7A7lFIp0VHhnynm9izx6TssdrIcVIESAlVjtnO2K8bg+Coew==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/smart-buffer": {
      "version": "4.2.0",
      "resolved": "https://registry.npmmirror.com/smart-buffer/-/smart-buffer-4.2.0.tgz",
      "integrity": "sha512-94hK0Hh8rPqQl2xXc3HsaBoOXKV20MToPkcXvwbISWLEs+64sBq5kFgn2kJDHb1Pry9yrP0dxrCI9RRci7RXKg==",
      "dev": true,
      "engines": {
        "node": ">= 6.0.0",
        "npm": ">= 3.0.0"
      }
    },
    "node_modules/socks": {
      "version": "2.8.3",
      "resolved": "https://registry.npmmirror.com/socks/-/socks-2.8.3.tgz",
      "integrity": "sha512-l5x7VUUWbjVFbafGLxPWkYsHIhEvmF85tbIeFZWc8ZPtoMyybuEhL7Jye/ooC4/d48FgOjSJXgsF/AJPYCW8Zw==",
      "dev": true,
      "dependencies": {
        "ip-address": "^9.0.5",
        "smart-buffer": "^4.2.0"
      },
      "engines": {
        "node": ">= 10.0.0",
        "npm": ">= 3.0.0"
      }
    },
    "node_modules/socks-proxy-agent": {
      "version": "8.0.4",
      "resolved": "https://registry.npmmirror.com/socks-proxy-agent/-/socks-proxy-agent-8.0.4.tgz",
      "integrity": "sha512-GNAq/eg8Udq2x0eNiFkr9gRg5bA7PXEWagQdeRX4cPSG+X/8V38v637gim9bjFptMk1QWsCTr0ttrJEiXbNnRw==",
      "dev": true,
      "dependencies": {
        "agent-base": "^7.1.1",
        "debug": "^4.3.4",
        "socks": "^2.8.3"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/sort-keys": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/sort-keys/-/sort-keys-2.0.0.tgz",
      "integrity": "sha512-/dPCrG1s3ePpWm6yBbxZq5Be1dXGLyLn9Z791chDC3NFrpkVbWGzkBwPN1knaciexFXgRJ7hzdnwZ4stHSDmjg==",
      "dependencies": {
        "is-plain-obj": "^1.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/sort-keys-length": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/sort-keys-length/-/sort-keys-length-1.0.1.tgz",
      "integrity": "sha512-GRbEOUqCxemTAk/b32F2xa8wDTs+Z1QHOkbhJDQTvv/6G3ZkbJ+frYWsTcc7cBB3Fu4wy4XlLCuNtJuMn7Gsvw==",
      "dependencies": {
        "sort-keys": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sort-keys-length/node_modules/sort-keys": {
      "version": "1.1.2",
      "resolved": "https://registry.npmmirror.com/sort-keys/-/sort-keys-1.1.2.tgz",
      "integrity": "sha512-vzn8aSqKgytVik0iwdBEi+zevbTYZogewTUM6dtpmGwEcdzbub/TX4bCzRhebDCRC3QzXgJsLRKB2V/Oof7HXg==",
      "dependencies": {
        "is-plain-obj": "^1.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/source-map": {
      "version": "0.6.1",
      "resolved": "https://registry.npmmirror.com/source-map/-/source-map-0.6.1.tgz",
      "integrity": "sha512-UjgapumWlbMhkBgzT7Ykc5YXUT46F0iKu8SGXq0bcwP5dz/h0Plj6enJqjz1Zbq2l5WaqYnrVbwWOWMyF3F47g==",
      "dev": true,
      "optional": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/source-map-js": {
      "version": "1.2.1",
      "resolved": "https://registry.npmmirror.com/source-map-js/-/source-map-js-1.2.1.tgz",
      "integrity": "sha512-UXWMKhLOwVKb728IUtQPXxfYU+usdybtUrK/8uGE8CQMvrhOpwvzDBwj0QhSL7MQc7vIsISBG8VQ8+IDQxpfQA==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/sprintf-js": {
      "version": "1.1.3",
      "resolved": "https://registry.npmmirror.com/sprintf-js/-/sprintf-js-1.1.3.tgz",
      "integrity": "sha512-Oo+0REFV59/rz3gfJNKQiBlwfHaSESl1pcGyABQsnnIfWOFt6JNj5gCog2U6MLZ//IGYD+nA8nI+mTShREReaA==",
      "dev": true
    },
    "node_modules/stdin-discarder": {
      "version": "0.2.2",
      "resolved": "https://registry.npmmirror.com/stdin-discarder/-/stdin-discarder-0.2.2.tgz",
      "integrity": "sha512-UhDfHmA92YAlNnCfhmq0VeNL5bDbiZGg7sZ2IvPsXubGkiNa9EC+tUTsjBRsYUAz87btI6/1wf4XoVvQ3uRnmQ==",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/strict-uri-encode": {
      "version": "1.1.0",
      "resolved": "https://registry.npmmirror.com/strict-uri-encode/-/strict-uri-encode-1.1.0.tgz",
      "integrity": "sha512-R3f198pcvnB+5IpnBlRkphuE9n46WyVl8I39W/ZUTZLz4nqSP/oLYUrcnJrw462Ds8he4YKMov2efsTIw1BDGQ==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/string_decoder": {
      "version": "1.1.1",
      "resolved": "https://registry.npmmirror.com/string_decoder/-/string_decoder-1.1.1.tgz",
      "integrity": "sha512-n/ShnvDi6FHbbVfviro+WojiFzv+s8MPMHBczVePfUpDJLwoLT0ht1l4YwBCbi8pJAveEEdnkHyPyTP/mzRfwg==",
      "dependencies": {
        "safe-buffer": "~5.1.0"
      }
    },
    "node_modules/string_decoder/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g=="
    },
    "node_modules/string-width": {
      "version": "7.2.0",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-7.2.0.tgz",
      "integrity": "sha512-tsaTIkKW9b4N+AEj+SVA+WhJzV7/zMhcSu78mLKWSk7cXMOSHsBKFWUs0fWwq8QyK3MgJBQRX6Gbi4kYbdvGkQ==",
      "dependencies": {
        "emoji-regex": "^10.3.0",
        "get-east-asian-width": "^1.0.0",
        "strip-ansi": "^7.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/string-width-cjs": {
      "name": "string-width",
      "version": "4.2.3",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A=="
    },
    "node_modules/string-width-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi": {
      "version": "7.1.0",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-7.1.0.tgz",
      "integrity": "sha512-iq6eVVI64nQQTRYq2KtEg2d2uU7LElhTJwsH4YzIHZshxlgZms/wIc4VoDQTlG/IvVIrBKG06CrZnp0qv7hkcQ==",
      "dependencies": {
        "ansi-regex": "^6.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/strip-ansi?sponsor=1"
      }
    },
    "node_modules/strip-ansi-cjs": {
      "name": "strip-ansi",
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-dirs": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/strip-dirs/-/strip-dirs-2.1.0.tgz",
      "integrity": "sha512-JOCxOeKLm2CAS73y/U4ZeZPTkE+gNVCzKt7Eox84Iej1LT/2pTWYpZKJuxwQpvX1LiZb1xokNR7RLfuBAa7T3g==",
      "dependencies": {
        "is-natural-number": "^4.0.1"
      }
    },
    "node_modules/strip-final-newline": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/strip-final-newline/-/strip-final-newline-3.0.0.tgz",
      "integrity": "sha512-dOESqjYr96iWYylGObzd39EuNTa5VJxyvVAEm5Jnh7KGo75V43Hk1odPQkNDyXNmUR6k+gEiDVXnjB8HJ3crXw==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/strip-json-comments": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/strip-json-comments/-/strip-json-comments-2.0.1.tgz",
      "integrity": "sha512-4gB8na07fecVVkOI6Rs4e7T6NOTki5EmL7TUduTs6bu3EdnSycntVJ4re8kgZA+wx9IueI2Y11bfbgwtzuE0KQ==",
      "dev": true,
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/strip-outer": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/strip-outer/-/strip-outer-1.0.1.tgz",
      "integrity": "sha512-k55yxKHwaXnpYGsOzg4Vl8+tDrWylxDEpknGjhTiZB8dFRU5rTo9CAzeycivxV3s+zlTKwrs6WxMxR95n26kwg==",
      "dependencies": {
        "escape-string-regexp": "^1.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/stubborn-fs": {
      "version": "1.2.5",
      "resolved": "https://registry.npmmirror.com/stubborn-fs/-/stubborn-fs-1.2.5.tgz",
      "integrity": "sha512-H2N9c26eXjzL/S/K+i/RHHcFanE74dptvvjM8iwzwbVcWY/zjBbgRqF3K0DY4+OD+uTTASTBvDoxPDaPN02D7g==",
      "dev": true
    },
    "node_modules/stylehacks": {
      "version": "7.0.4",
      "resolved": "https://registry.npmmirror.com/stylehacks/-/stylehacks-7.0.4.tgz",
      "integrity": "sha512-i4zfNrGMt9SB4xRK9L83rlsFCgdGANfeDAYacO1pkqcE7cRHPdWHwnKZVz7WY17Veq/FvyYsRAU++Ga+qDFIww==",
      "dev": true,
      "dependencies": {
        "browserslist": "^4.23.3",
        "postcss-selector-parser": "^6.1.2"
      },
      "engines": {
        "node": "^18.12.0 || ^20.9.0 || >=22.0"
      },
      "peerDependencies": {
        "postcss": "^8.4.31"
      }
    },
    "node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmmirror.com/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/supports-preserve-symlinks-flag": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/supports-preserve-symlinks-flag/-/supports-preserve-symlinks-flag-1.0.0.tgz",
      "integrity": "sha512-ot0WnXS9fgdkgIcePe6RHNk1WA8+muPa6cSjeR3V8K27q9BB1rTE3R1p7Hv0z1ZyAc8s6Vvv8DIyWf681MAt0w==",
      "dev": true,
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/svgo": {
      "version": "3.3.2",
      "resolved": "https://registry.npmmirror.com/svgo/-/svgo-3.3.2.tgz",
      "integrity": "sha512-OoohrmuUlBs8B8o6MB2Aevn+pRIH9zDALSR+6hhqVfa6fRwG/Qw9VUMSMW9VNg2CFc/MTIfabtdOVl9ODIJjpw==",
      "dev": true,
      "dependencies": {
        "@trysound/sax": "0.2.0",
        "commander": "^7.2.0",
        "css-select": "^5.1.0",
        "css-tree": "^2.3.1",
        "css-what": "^6.1.0",
        "csso": "^5.0.5",
        "picocolors": "^1.0.0"
      },
      "bin": {
        "svgo": "bin/svgo"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/svgo"
      }
    },
    "node_modules/svgo/node_modules/commander": {
      "version": "7.2.0",
      "resolved": "https://registry.npmmirror.com/commander/-/commander-7.2.0.tgz",
      "integrity": "sha512-QrWXB+ZQSVPmIWIhtEO9H+gwHaMGYiF5ChvoJ+K9ZGHG/sVsa6yiesAD1GC/x46sET00Xlwo1u49RVVVzvcSkw==",
      "dev": true,
      "engines": {
        "node": ">= 10"
      }
    },
    "node_modules/tar-stream": {
      "version": "1.6.2",
      "resolved": "https://registry.npmmirror.com/tar-stream/-/tar-stream-1.6.2.tgz",
      "integrity": "sha512-rzS0heiNf8Xn7/mpdSVVSMAWAoy9bfb1WOTYC78Z0UQKeKa/CWS8FOq0lKGNa8DWKAn9gxjCvMLYc5PGXYlK2A==",
      "dependencies": {
        "bl": "^1.0.0",
        "buffer-alloc": "^1.2.0",
        "end-of-stream": "^1.0.0",
        "fs-constants": "^1.0.0",
        "readable-stream": "^2.3.0",
        "to-buffer": "^1.1.1",
        "xtend": "^4.0.0"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/through": {
      "version": "2.3.8",
      "resolved": "https://registry.npmmirror.com/through/-/through-2.3.8.tgz",
      "integrity": "sha512-w89qg7PI8wAdvX60bMDP+bFoD5Dvhm9oLheFp5O4a2QF0cSBGsBX4qZmadPMvVqlLJBBci+WqGGOAPvcDeNSVg=="
    },
    "node_modules/timed-out": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/timed-out/-/timed-out-4.0.1.tgz",
      "integrity": "sha512-G7r3AhovYtr5YKOWQkta8RKAPb+J9IsO4uVmzjl8AZwfhs8UcUwTiD6gcJYSgOtzyjvQKrKYn41syHbUWMkafA==",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/tinyglobby": {
      "version": "0.2.10",
      "resolved": "https://registry.npmmirror.com/tinyglobby/-/tinyglobby-0.2.10.tgz",
      "integrity": "sha512-Zc+8eJlFMvgatPZTl6A9L/yht8QqdmUNtURHaKZLmKBE12hNPSrqNkUp2cs3M/UKmNVVAMFQYSjYIVHDjW5zew==",
      "dev": true,
      "dependencies": {
        "fdir": "^6.4.2",
        "picomatch": "^4.0.2"
      },
      "engines": {
        "node": ">=12.0.0"
      }
    },
    "node_modules/tmp": {
      "version": "0.0.33",
      "resolved": "https://registry.npmmirror.com/tmp/-/tmp-0.0.33.tgz",
      "integrity": "sha512-jRCJlojKnZ3addtTOjdIqoRuPEKBvNXcGYqzO6zWZX8KfKEpnGY5jfggJQ3EjKuu8D4bJRr0y+cYJFmYbImXGw==",
      "dev": true,
      "dependencies": {
        "os-tmpdir": "~1.0.2"
      },
      "engines": {
        "node": ">=0.6.0"
      }
    },
    "node_modules/to-buffer": {
      "version": "1.1.1",
      "resolved": "https://registry.npmmirror.com/to-buffer/-/to-buffer-1.1.1.tgz",
      "integrity": "sha512-lx9B5iv7msuFYE3dytT+KE5tap+rNYw+K4jVkb9R/asAb+pbBSM17jtunHplhBe6RRJdZx3Pn2Jph24O32mOVg=="
    },
    "node_modules/to-regex-range": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/to-regex-range/-/to-regex-range-5.0.1.tgz",
      "integrity": "sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==",
      "dev": true,
      "dependencies": {
        "is-number": "^7.0.0"
      },
      "engines": {
        "node": ">=8.0"
      }
    },
    "node_modules/trim-repeated": {
      "version": "1.0.0",
      "resolved": "https://registry.npmmirror.com/trim-repeated/-/trim-repeated-1.0.0.tgz",
      "integrity": "sha512-pkonvlKk8/ZuR0D5tLW8ljt5I8kmxp2XKymhepUeOdCEfKpZaktSArkLHZt76OB1ZvO9bssUsDty4SWhLvZpLg==",
      "dependencies": {
        "escape-string-regexp": "^1.0.2"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/tslib": {
      "version": "2.8.1",
      "resolved": "https://registry.npmmirror.com/tslib/-/tslib-2.8.1.tgz",
      "integrity": "sha512-oJFu94HQb+KVduSUQL7wnpmqnfmLsOA/nAh6b6EH0wCEoK0/mPeXU6c3wKDV83MkOuHPRHtSXKKU99IBazS/2w==",
      "dev": true
    },
    "node_modules/tunnel-agent": {
      "version": "0.6.0",
      "resolved": "https://registry.npmmirror.com/tunnel-agent/-/tunnel-agent-0.6.0.tgz",
      "integrity": "sha512-McnNiV1l8RYeY8tBgEpuodCC1mLUdbSN+CYBL7kJsJNInOP8UjDDEwdk6Mw60vdLLrr5NHKZhMAOSrR2NZuQ+w==",
      "dependencies": {
        "safe-buffer": "^5.0.1"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/type-fest": {
      "version": "0.21.3",
      "resolved": "https://registry.npmmirror.com/type-fest/-/type-fest-0.21.3.tgz",
      "integrity": "sha512-t0rzBq87m3fVcduHDUFhKmyyX+9eo6WQjZvf51Ea/M0Q7+T374Jp1aUiyUl0GKxp8M/OETVHSDvmkyPgvX+X2w==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/typescript": {
      "version": "5.6.3",
      "resolved": "https://registry.npmmirror.com/typescript/-/typescript-5.6.3.tgz",
      "integrity": "sha512-hjcS1mhfuyi4WW8IWtjP7brDrG2cuDZukyrYrSauoXGNgx0S7zceP07adYkJycEr56BOUTNPzbInooiN3fn1qw==",
      "dev": true,
      "peer": true,
      "bin": {
        "tsc": "bin/tsc",
        "tsserver": "bin/tsserver"
      },
      "engines": {
        "node": ">=14.17"
      }
    },
    "node_modules/ufo": {
      "version": "1.5.4",
      "resolved": "https://registry.npmmirror.com/ufo/-/ufo-1.5.4.tgz",
      "integrity": "sha512-UsUk3byDzKd04EyoZ7U4DOlxQaD14JUKQl6/P7wiX4FNvUfm3XL246n9W5AmqwW5RSFJ27NAuM0iLscAOYUiGQ==",
      "dev": true
    },
    "node_modules/unbuild": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/unbuild/-/unbuild-2.0.0.tgz",
      "integrity": "sha512-JWCUYx3Oxdzvw2J9kTAp+DKE8df/BnH/JTSj6JyA4SH40ECdFu7FoJJcrm8G92B7TjofQ6GZGjJs50TRxoH6Wg==",
      "dev": true,
      "dependencies": {
        "@rollup/plugin-alias": "^5.0.0",
        "@rollup/plugin-commonjs": "^25.0.4",
        "@rollup/plugin-json": "^6.0.0",
        "@rollup/plugin-node-resolve": "^15.2.1",
        "@rollup/plugin-replace": "^5.0.2",
        "@rollup/pluginutils": "^5.0.3",
        "chalk": "^5.3.0",
        "citty": "^0.1.2",
        "consola": "^3.2.3",
        "defu": "^6.1.2",
        "esbuild": "^0.19.2",
        "globby": "^13.2.2",
        "hookable": "^5.5.3",
        "jiti": "^1.19.3",
        "magic-string": "^0.30.3",
        "mkdist": "^1.3.0",
        "mlly": "^1.4.0",
        "pathe": "^1.1.1",
        "pkg-types": "^1.0.3",
        "pretty-bytes": "^6.1.1",
        "rollup": "^3.28.1",
        "rollup-plugin-dts": "^6.0.0",
        "scule": "^1.0.0",
        "untyped": "^1.4.0"
      },
      "bin": {
        "unbuild": "dist/cli.mjs"
      },
      "peerDependencies": {
        "typescript": "^5.1.6"
      },
      "peerDependenciesMeta": {
        "typescript": {
          "optional": true
        }
      }
    },
    "node_modules/unbzip2-stream": {
      "version": "1.4.3",
      "resolved": "https://registry.npmmirror.com/unbzip2-stream/-/unbzip2-stream-1.4.3.tgz",
      "integrity": "sha512-mlExGW4w71ebDJviH16lQLtZS32VKqsSfk80GCfUlwT/4/hNRFsoscrF/c++9xinkMzECL1uL9DDwXqFWkruPg==",
      "dependencies": {
        "buffer": "^5.2.1",
        "through": "^2.3.8"
      }
    },
    "node_modules/unicorn-magic": {
      "version": "0.1.0",
      "resolved": "https://registry.npmmirror.com/unicorn-magic/-/unicorn-magic-0.1.0.tgz",
      "integrity": "sha512-lRfVq8fE8gz6QMBuDM6a+LO3IAzTi05H6gCVaUpir2E1Rwpo4ZUog45KpNXKC/Mn3Yb9UDuHumeFTo9iV/D9FQ==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/universal-user-agent": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/universal-user-agent/-/universal-user-agent-6.0.1.tgz",
      "integrity": "sha512-yCzhz6FN2wU1NiiQRogkTQszlQSlpWaw8SvVegAc+bDxbzHgh1vX8uIe8OYyMH6DwH+sdTJsgMl36+mSMdRJIQ==",
      "dev": true
    },
    "node_modules/universalify": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/universalify/-/universalify-2.0.1.tgz",
      "integrity": "sha512-gptHNQghINnc/vTGIk0SOFGFNXw7JVrlRUtConJRlvaw6DuX0wO5Jeko9sWrMBhh+PsYAZ7oXAiOnf/UKogyiw==",
      "engines": {
        "node": ">= 10.0.0"
      }
    },
    "node_modules/untyped": {
      "version": "1.5.1",
      "resolved": "https://registry.npmmirror.com/untyped/-/untyped-1.5.1.tgz",
      "integrity": "sha512-reBOnkJBFfBZ8pCKaeHgfZLcehXtM6UTxc+vqs1JvCps0c4amLNp3fhdGBZwYp+VLyoY9n3X5KOP7lCyWBUX9A==",
      "dev": true,
      "dependencies": {
        "@babel/core": "^7.25.7",
        "@babel/standalone": "^7.25.7",
        "@babel/types": "^7.25.7",
        "defu": "^6.1.4",
        "jiti": "^2.3.1",
        "mri": "^1.2.0",
        "scule": "^1.3.0"
      },
      "bin": {
        "untyped": "dist/cli.mjs"
      }
    },
    "node_modules/untyped/node_modules/jiti": {
      "version": "2.3.3",
      "resolved": "https://registry.npmmirror.com/jiti/-/jiti-2.3.3.tgz",
      "integrity": "sha512-EX4oNDwcXSivPrw2qKH2LB5PoFxEvgtv2JgwW0bU858HoLQ+kutSvjLMUqBd0PeJYEinLWhoI9Ol0eYMqj/wNQ==",
      "dev": true,
      "bin": {
        "jiti": "lib/jiti-cli.mjs"
      }
    },
    "node_modules/update-browserslist-db": {
      "version": "1.1.1",
      "resolved": "https://registry.npmmirror.com/update-browserslist-db/-/update-browserslist-db-1.1.1.tgz",
      "integrity": "sha512-R8UzCaa9Az+38REPiJ1tXlImTJXlVfgHZsglwBD/k6nj76ctsH1E3q4doGrukiLQd3sGQYu56r5+lo5r94l29A==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "dependencies": {
        "escalade": "^3.2.0",
        "picocolors": "^1.1.0"
      },
      "bin": {
        "update-browserslist-db": "cli.js"
      },
      "peerDependencies": {
        "browserslist": ">= 4.21.0"
      }
    },
    "node_modules/update-notifier": {
      "version": "7.3.1",
      "resolved": "https://registry.npmmirror.com/update-notifier/-/update-notifier-7.3.1.tgz",
      "integrity": "sha512-+dwUY4L35XFYEzE+OAL3sarJdUioVovq+8f7lcIJ7wnmnYQV5UD1Y/lcwaMSyaQ6Bj3JMj1XSTjZbNLHn/19yA==",
      "dev": true,
      "dependencies": {
        "boxen": "^8.0.1",
        "chalk": "^5.3.0",
        "configstore": "^7.0.0",
        "is-in-ci": "^1.0.0",
        "is-installed-globally": "^1.0.0",
        "is-npm": "^6.0.0",
        "latest-version": "^9.0.0",
        "pupa": "^3.1.0",
        "semver": "^7.6.3",
        "xdg-basedir": "^5.1.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/yeoman/update-notifier?sponsor=1"
      }
    },
    "node_modules/url-join": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/url-join/-/url-join-5.0.0.tgz",
      "integrity": "sha512-n2huDr9h9yzd6exQVnH/jU5mr+Pfx08LRXXZhkLLetAMESRj+anQsTAh940iMrIetKAmry9coFuZQ2jY8/p3WA==",
      "dev": true,
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      }
    },
    "node_modules/url-parse-lax": {
      "version": "3.0.0",
      "resolved": "https://registry.npmmirror.com/url-parse-lax/-/url-parse-lax-3.0.0.tgz",
      "integrity": "sha512-NjFKA0DidqPa5ciFcSrXnAltTtzz84ogy+NebPvfEgAck0+TNg4UJ4IN+fB7zRZfbgUf0syOo9MDxFkDSMuFaQ==",
      "dependencies": {
        "prepend-http": "^2.0.0"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/url-to-options": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/url-to-options/-/url-to-options-1.0.1.tgz",
      "integrity": "sha512-0kQLIzG4fdk/G5NONku64rSH/x32NOA39LVQqlK8Le6lvTF6GGRJpqaQFGgU+CLwySIqBSMdwYM0sYcW9f6P4A==",
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw=="
    },
    "node_modules/wcwidth": {
      "version": "1.0.1",
      "resolved": "https://registry.npmmirror.com/wcwidth/-/wcwidth-1.0.1.tgz",
      "integrity": "sha512-XHPEwS0q6TaxcvG85+8EYkbiCux2XtWG2mkc47Ng2A77BQu9+DqIOJldST4HgPkuea7dvKSj5VgX3P1d4rW8Tg==",
      "dev": true,
      "dependencies": {
        "defaults": "^1.0.3"
      }
    },
    "node_modules/when-exit": {
      "version": "2.1.3",
      "resolved": "https://registry.npmmirror.com/when-exit/-/when-exit-2.1.3.tgz",
      "integrity": "sha512-uVieSTccFIr/SFQdFWN/fFaQYmV37OKtuaGphMAzi4DmmUlrvRBJW5WSLkHyjNQY/ePJMz3LoiX9R3yy1Su6Hw==",
      "dev": true
    },
    "node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmmirror.com/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/widest-line": {
      "version": "5.0.0",
      "resolved": "https://registry.npmmirror.com/widest-line/-/widest-line-5.0.0.tgz",
      "integrity": "sha512-c9bZp7b5YtRj2wOe6dlj32MK+Bx/M/d+9VB2SHM1OtsUHR0aV0tdP6DWh/iMt0kWi1t5g1Iudu6hQRNd1A4PVA==",
      "dev": true,
      "dependencies": {
        "string-width": "^7.0.0"
      },
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/wildcard-match": {
      "version": "5.1.3",
      "resolved": "https://registry.npmmirror.com/wildcard-match/-/wildcard-match-5.1.3.tgz",
      "integrity": "sha512-a95hPUk+BNzSGLntNXYxsjz2Hooi5oL7xOfJR6CKwSsSALh7vUNuTlzsrZowtYy38JNduYFRVhFv19ocqNOZlg==",
      "dev": true
    },
    "node_modules/windows-release": {
      "version": "5.1.1",
      "resolved": "https://registry.npmmirror.com/windows-release/-/windows-release-5.1.1.tgz",
      "integrity": "sha512-NMD00arvqcq2nwqc5Q6KtrSRHK+fVD31erE5FEMahAw5PmVCgD7MUXodq3pdZSUkqA9Cda2iWx6s1XYwiJWRmw==",
      "dev": true,
      "dependencies": {
        "execa": "^5.1.1"
      },
      "engines": {
        "node": "^12.20.0 || ^14.13.1 || >=16.0.0"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/windows-release/node_modules/execa": {
      "version": "5.1.1",
      "resolved": "https://registry.npmmirror.com/execa/-/execa-5.1.1.tgz",
      "integrity": "sha512-8uSpZZocAZRBAPIEINJj3Lo9HyGitllczc27Eh5YYojjMFMn8yHMDMaUHE2Jqfq05D/wucwI4JGURyXt1vchyg==",
      "dev": true,
      "dependencies": {
        "cross-spawn": "^7.0.3",
        "get-stream": "^6.0.0",
        "human-signals": "^2.1.0",
        "is-stream": "^2.0.0",
        "merge-stream": "^2.0.0",
        "npm-run-path": "^4.0.1",
        "onetime": "^5.1.2",
        "signal-exit": "^3.0.3",
        "strip-final-newline": "^2.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sindresorhus/execa?sponsor=1"
      }
    },
    "node_modules/windows-release/node_modules/get-stream": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/get-stream/-/get-stream-6.0.1.tgz",
      "integrity": "sha512-ts6Wi+2j3jQjqi70w5AlN8DFnkSwC+MqmxEzdEALB2qXZYV3X/b1CTfgPLGJNMeAWxdPfU8FO1ms3NUfaHCPYg==",
      "dev": true,
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/windows-release/node_modules/human-signals": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/human-signals/-/human-signals-2.1.0.tgz",
      "integrity": "sha512-B4FFZ6q/T2jhhksgkbEW3HBvWIfDW85snkQgawt07S7J5QXTk6BkNV+0yAeZrM5QpMAdYlocGoljn0sJ/WQkFw==",
      "dev": true,
      "engines": {
        "node": ">=10.17.0"
      }
    },
    "node_modules/windows-release/node_modules/is-stream": {
      "version": "2.0.1",
      "resolved": "https://registry.npmmirror.com/is-stream/-/is-stream-2.0.1.tgz",
      "integrity": "sha512-hFoiJiTl63nn+kstHGBtewWSKnQLpyb155KHheA1l39uvtO9nWIop1p3udqPcUd/xbF1VLMO4n7OI6p7RbngDg==",
      "dev": true,
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/windows-release/node_modules/mimic-fn": {
      "version": "2.1.0",
      "resolved": "https://registry.npmmirror.com/mimic-fn/-/mimic-fn-2.1.0.tgz",
      "integrity": "sha512-OqbOk5oEQeAZ8WXWydlu9HJjz9WVdEIvamMCcXmuqUYjTknH/sqsWvhQ3vgwKFRR1HpjvNBKQ37nbJgYzGqGcg==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/windows-release/node_modules/npm-run-path": {
      "version": "4.0.1",
      "resolved": "https://registry.npmmirror.com/npm-run-path/-/npm-run-path-4.0.1.tgz",
      "integrity": "sha512-S48WzZW777zhNIrn7gxOlISNAqi9ZC/uQFnRdbeIHhZhCA6UqpkOT8T1G7BvfdgP4Er8gF4sUbaS0i7QvIfCWw==",
      "dev": true,
      "dependencies": {
        "path-key": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/windows-release/node_modules/onetime": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/onetime/-/onetime-5.1.2.tgz",
      "integrity": "sha512-kbpaSSGJTWdAY5KPVeMOKXSrPtr8C8C7wodJbcsd51jRnmD+GZu8Y0VoU6Dm5Z4vWr0Ig/1NKuWRKf7j5aaYSg==",
      "dev": true,
      "dependencies": {
        "mimic-fn": "^2.1.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/windows-release/node_modules/signal-exit": {
      "version": "3.0.7",
      "resolved": "https://registry.npmmirror.com/signal-exit/-/signal-exit-3.0.7.tgz",
      "integrity": "sha512-wnD2ZE+l+SPC/uoS0vXeE9L1+0wuaMqKlfz9AMUo38JsyLSBWSFcHR1Rri62LZc12vLr1gb3jl7iwQhgwpAbGQ==",
      "dev": true
    },
    "node_modules/windows-release/node_modules/strip-final-newline": {
      "version": "2.0.0",
      "resolved": "https://registry.npmmirror.com/strip-final-newline/-/strip-final-newline-2.0.0.tgz",
      "integrity": "sha512-BrpvfNAE3dcvq7ll3xVumzjKjZQ5tI1sEUIKr3Uoks0XUl45St3FlatVqef9prk4jRDzhW6WZg+3bk93y6pLjA==",
      "dev": true,
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/wrap-ansi": {
      "version": "8.1.0",
      "resolved": "https://registry.npmmirror.com/wrap-ansi/-/wrap-ansi-8.1.0.tgz",
      "integrity": "sha512-si7QWI6zUMq56bESFvagtmzMdGOtoxfR+Sez11Mobfc7tm+VkUckk9bW2UeffTGVUbOksxmSw0AA2gs8g71NCQ==",
      "dependencies": {
        "ansi-styles": "^6.1.0",
        "string-width": "^5.0.1",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs": {
      "name": "wrap-ansi",
      "version": "7.0.0",
      "resolved": "https://registry.npmmirror.com/wrap-ansi/-/wrap-ansi-7.0.0.tgz",
      "integrity": "sha512-YVGIj2kamLSTxw6NsZjoBxfSwsn0ycdesmc4p+Q21c5zPuZ1pl+NfxVdxPtdHvmNVOQ6XSYG4AUtyt/Fi7D16Q==",
      "dependencies": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmmirror.com/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmmirror.com/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A=="
    },
    "node_modules/wrap-ansi-cjs/node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmmirror.com/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi/node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmmirror.com/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg=="
    },
    "node_modules/wrap-ansi/node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmmirror.com/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmmirror.com/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha512-l4Sp/DRseor9wL6EvV2+TuQn63dMkPjZ/sp9XkghTEbV9KlPS1xUsZ3u7/IQO4wxtcFB4bgpQPRcR3QCvezPcQ=="
    },
    "node_modules/xdg-basedir": {
      "version": "5.1.0",
      "resolved": "https://registry.npmmirror.com/xdg-basedir/-/xdg-basedir-5.1.0.tgz",
      "integrity": "sha512-GCPAHLvrIH13+c0SuacwvRYj2SxJXQ4kaVTT5xgL3kPrz56XxkF21IGhjSE1+W0aw7gpBWRGXLCPnPby6lSpmQ==",
      "dev": true,
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/xtend": {
      "version": "4.0.2",
      "resolved": "https://registry.npmmirror.com/xtend/-/xtend-4.0.2.tgz",
      "integrity": "sha512-LKYU1iAXJXUgAXn9URjiu+MWhyUXHsvfp7mcuYm9dSUKK0/CjtrUwFAxD82/mCWbtLsGjFIad0wIsod4zrTAEQ==",
      "engines": {
        "node": ">=0.4"
      }
    },
    "node_modules/yallist": {
      "version": "3.1.1",
      "resolved": "https://registry.npmmirror.com/yallist/-/yallist-3.1.1.tgz",
      "integrity": "sha512-a4UGQaWPH59mOXUYnAG2ewncQS4i4F43Tv3JoAM+s2VDAmS9NsK8GpDMLrCHPksFT7h3K6TOoUNn2pb7RoXx4g==",
      "dev": true
    },
    "node_modules/yargs-parser": {
      "version": "21.1.1",
      "resolved": "https://registry.npmmirror.com/yargs-parser/-/yargs-parser-21.1.1.tgz",
      "integrity": "sha512-tVpsJW7DdjecAiFpbIB1e3qxIQsE6NoPc5/eTdrbbIC4h0LVsWhnoa3g+m2HclBIujHzsxZ4VJVA+GUuc2/LBw==",
      "dev": true,
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/yauzl": {
      "version": "2.10.0",
      "resolved": "https://registry.npmmirror.com/yauzl/-/yauzl-2.10.0.tgz",
      "integrity": "sha512-p4a9I6X6nu6IhoGmBqAcbJy1mlC4j27vEPZX9F4L4/vZT3Lyq1VkFHw/V/PUcB9Buo+DG3iHkT0x3Qya58zc3g==",
      "dependencies": {
        "buffer-crc32": "~0.2.3",
        "fd-slicer": "~1.1.0"
      }
    },
    "node_modules/yoctocolors-cjs": {
      "version": "2.1.2",
      "resolved": "https://registry.npmmirror.com/yoctocolors-cjs/-/yoctocolors-cjs-2.1.2.tgz",
      "integrity": "sha512-cYVsTjKl8b+FrnidjibDWskAv7UKOfcwaVZdp/it9n1s9fU3IkgDbhdIRKCW4JDsAlECJY0ytoVPT3sK6kideA==",
      "dev": true,
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    }
  }
}
