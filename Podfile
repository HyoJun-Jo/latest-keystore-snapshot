platform :ios, '9.0'

target 'TrustKeystore' do
  use_frameworks!
  pod 'BigInt', '~> 3.0'
  pod 'CryptoSwift', '~> 1.0'
  pod 'secp256k1.swift'
  pod 'TrezorCrypto', inhibit_warnings: true

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
