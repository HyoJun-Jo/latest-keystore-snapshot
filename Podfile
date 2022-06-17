platform :ios, '11.0'

target 'TrustKeystore' do
  use_frameworks!
  pod 'BigInt', '~> 3.0'
  pod 'CryptoSwift', '1.5.1'
  pod 'secp256k1.swift'
  pod 'TrezorCrypto', inhibit_warnings: true

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
