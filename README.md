- name: Setup Android
  uses: android-actions/setup-android@v3
  with:
    packages: tools platform-tools

- name: Accept Android licenses
  run: yes | sdkmanager --licenses
