# This file is automatically processed to create .DEPS.git which is the file
# that gclient uses under git.
#
# See http://code.google.com/p/chromium/wiki/UsingGit
#
# To test manually, run:
#   python tools/deps2git/deps2git.py -o .DEPS.git -w <gclientdir>
# where <gcliendir> is the absolute path to the directory containing the
# .gclient file (the parent of 'src').
#
# Then commit .DEPS.git locally (gclient doesn't like dirty trees) and run
#   gclient sync..
# Verify the thing happened you wanted. Then revert your .DEPS.git change
# DO NOT CHECK IN CHANGES TO .DEPS.git upstream. It will be automatically
# updated by a bot when you modify this one.
#
# When adding a new dependency, please update the top-level .gitignore file
# to list the dependency's destination directory.

vars = {
  'chromium_git': 'https://chromium.googlesource.com',
  'dart_git': 'https://dart.googlesource.com',
  'skia_git': 'https://skia.googlesource.com',
  'skia_revision': '9adc82c73df0ef25b708cae8aa48ef9c39ed4c67',

  # When updating the Dart revision, ensure that all entries that are
  # dependencies of Dart are also updated to match the entries in the
  # Dart SDK's DEPS file for that revision of Dart. The DEPS file for
  # Dart is: https://github.com/dart-lang/sdk/blob/master/DEPS.
  # You can use //tools/dart/create_updated_flutter_deps.py to produce
  # updated revision list of existing dependencies.
  'dart_revision': '1f1592edce7122ff657d9538d58d9cce0cae46e6',

  # WARNING: DO NOT EDIT MANUALLY
  # The lines between blank lines above and below are generated by a script. See create_updated_flutter_deps.py
  'dart_args_tag': '1.4.4',
  'dart_async_tag': '2.0.8',
  'dart_bazel_worker_tag': 'bazel_worker-v0.1.20',
  'dart_boolean_selector_tag': '1.0.4',
  'dart_boringssl_gen_rev': 'bbf52f18f425e29b1185f2f6753bec02ed8c5880',
  'dart_boringssl_rev': '702e2b6d3831486535e958f262a05c75a5cb312e',
  'dart_charcode_tag': 'v1.1.2',
  'dart_cli_util_rev': '4ad7ccbe3195fd2583b30f86a86697ef61e80f41',
  'dart_collection_tag': '1.14.11',
  'dart_convert_tag': '2.0.2',
  'dart_crypto_tag': '2.0.6',
  'dart_csslib_tag': '0.15.0',
  'dart_dart2js_info_tag': '0.6.0',
  'dart_dart_style_tag': '1.2.7',
  'dart_dartdoc_tag': 'v0.28.2',
  'dart_fixnum_tag': '0.10.9',
  'dart_glob_tag': '1.1.7',
  'dart_html_tag': '0.14.0+1',
  'dart_http_multi_server_tag': '2.0.5',
  'dart_http_parser_tag': '3.1.3',
  'dart_http_retry_tag': '0.1.1',
  'dart_http_tag': '0.12.0+2',
  'dart_http_throttle_tag': '1.0.2',
  'dart_intl_tag': '0.15.7',
  'dart_json_rpc_2_tag': '2.0.9',
  'dart_linter_tag': '0.1.86',
  'dart_logging_tag': '0.11.3+2',
  'dart_markdown_tag': '2.0.3',
  'dart_matcher_tag': '0.12.3',
  'dart_mime_tag': '0.9.6+2',
  'dart_mockito_tag': 'd39ac507483b9891165e422ec98d9fb480037c8b',
  'dart_mustache_tag': '5e81b12215566dbe2473b2afd01a8a8aedd56ad9',
  'dart_oauth2_tag': '1.2.1',
  'dart_observatory_pub_packages_rev': '0894122173b0f98eb08863a7712e78407d4477bc',
  'dart_package_config_tag': '1.0.5',
  'dart_package_resolver_tag': '1.0.10',
  'dart_path_tag': '1.6.2',
  'dart_pedantic_tag': 'v1.5.0',
  'dart_pool_tag': '1.3.6',
  'dart_protobuf_rev': '0c77167b16d00b561a6055bfe26690af7f26ae88',
  'dart_pub_rev': '8c363fe26f059c3063f1129adbb3c4e22a8ce954',
  'dart_pub_semver_tag': '1.4.2',
  'dart_quiver_tag': '2.0.0+1',
  'dart_resource_rev': '2.1.5',
  'dart_root_certificates_rev': '16ef64be64c7dfdff2b9f4b910726e635ccc519e',
  'dart_shelf_packages_handler_tag': '1.0.4',
  'dart_shelf_static_rev': 'v0.2.8',
  'dart_shelf_tag': '0.7.3+3',
  'dart_shelf_web_socket_tag': '0.2.2+3',
  'dart_source_map_stack_trace_tag': '1.1.5',
  'dart_source_maps_tag': '8af7cc1a1c3a193c1fba5993ce22a546a319c40e',
  'dart_source_span_tag': '1.5.5',
  'dart_stack_trace_tag': '1.9.3',
  'dart_stream_channel_tag': '2.0.0',
  'dart_string_scanner_tag': '1.0.3',
  'dart_term_glyph_tag': '1.0.1',
  'dart_test_reflective_loader_tag': '0.1.8',
  'dart_test_tag': 'test-v1.6.1',
  'dart_typed_data_tag': '1.1.6',
  'dart_usage_tag': '3.4.0',
  'dart_watcher_rev': '0.9.7+12',
  'dart_web_socket_channel_tag': '1.0.9',
  'dart_yaml_tag': '2.1.15',

  # Build bot tooling for iOS
  'ios_tools_revision': '69b7c1b160e7107a6a98d948363772dc9caea46f',

  'buildtools_revision': 'bac220c15490dcf7b7d8136f75100bbc77e8d217',

  # Checkout Android dependencies only on platforms where we build for Android targets.
  'download_android_deps': 'host_os == "mac" or host_os == "linux"',

  # Checkout Windows dependencies only if we are building on Windows.
  'download_windows_deps' : 'host_os == "win"',
}

# Only these hosts are allowed for dependencies in this DEPS file.
# If you need to add a new host, contact chrome infrastructure team.
allowed_hosts = [
  'chromium.googlesource.com',
  'fuchsia.googlesource.com',
  'github.com',
  'skia.googlesource.com',
]

deps = {

   # Chromium-style
   #
   # As part of integrating with Fuchsia, we should eventually remove all these
   # Chromium-style dependencies.

  
   'src/third_party/android_tools/ndk': {
     'packages': [
       {
        'package': 'flutter/android/ndk/${{platform}}',
        'version': 'version:r19b'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/build-tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/build-tools/${{platform}}',
        'version': 'version:28.0.3'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/platform-tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/platform-tools/${{platform}}',
        'version': 'version:28.0.1'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/platforms': {
     'packages': [
       {
        'package': 'flutter/android/sdk/platforms',
        'version': 'version:28r6'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },

  'src/third_party/android_tools/sdk/tools': {
     'packages': [
       {
        'package': 'flutter/android/sdk/tools/${{platform}}',
        'version': 'version:26.1.1'
       }
     ],
     'condition': 'download_android_deps',
     'dep_type': 'cipd',
   },
}

hooks = [
  {
    # This clobbers when necessary (based on get_landmines.py). It must be the
    # first hook so that other things that get/generate into the output
    # directory will not subsequently be clobbered.
    'name': 'landmines',
    'pattern': '.',
    'action': [
        'python',
        'src/build/landmines.py',
    ],
  },
  {
    # Update the Windows toolchain if necessary.
    'name': 'win_toolchain',
    'condition': 'download_windows_deps',
    'pattern': '.',
    'action': ['python', 'src/build/vs_toolchain.py', 'update'],
  },
  {
    # Pull prebuilt dart sdk.
    'name': 'dart',
    'pattern': '.',
    'action': ['python', 'src/tools/dart/update.py'],
  },
  {
    'name': 'download_android_support',
    'pattern': '.',
    'condition': 'download_android_deps',
    'action': [
        'python',
        'src/flutter/tools/android_support/download_android_support.py',
    ],
  },
  {
    'name': 'buildtools',
    'pattern': '.',
    'action': [
      'python',
      'src/tools/buildtools/update.py',
    ],
  },
  {
    'name': 'generate_package_files',
    'pattern': '.',
    'cwd': 'src/',
    'action': ['python', 'flutter/tools/generate_package_files.py'],
  },
  {
    # Ensure that we don't accidentally reference any .pyc files whose
    # corresponding .py files have already been deleted.
    'name': 'remove_stale_pyc_files',
    'pattern': 'src/tools/.*\\.py',
    'action': [
        'python',
        'src/tools/remove_stale_pyc_files.py',
        'src/tools',
    ],
  },
  {
    'name': '7zip',
    'pattern': '.',
    'condition': 'download_windows_deps',
    'action': [
      'download_from_google_storage',
      '--no_auth',
      '--no_resume',
      '--bucket',
      'dart-dependencies',
      '--platform=win32',
      '--extract',
      '-s',
      'src/third_party/dart/third_party/7zip.tar.gz.sha1',
    ],
  },
]
