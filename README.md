# Alignedlayer_Proof

Aligned Layer 'da proof gönderdim, ödül ihtimali için. 

sudo apt update -y && sudo apt upgrade -y

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
source /root/.bashrc

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash

# Alttaki bloğu toplu girin.
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci.elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com

Akabinde bir çıktı alın, linke tıklayın Verified olmasını bekleyin.

Son olarakta ekran görüntüsünü ailgned'i etiketleyerek - TX HASH İLE BİRLİKTE tweetleyin.

Tweet'i discorda testnet kanalında paylaşın.
