<script>
  const CHANNEL_URL = "https://www.youtube.com/@jk-trick2625";
  const VIDEO_URL   = "https://youtu.be/wfw7e2vh3zc?si=4vk6hJgdTIOxz2Rm";

  // El resto del código permanece igual:

  const modal = document.getElementById('subscribe-modal');
  const openGateBtn = document.getElementById('open-gate');
  const openVideoBtn = document.getElementById('open-video');
  const robotCheck = document.getElementById('robot-check');
  const notRobotBtn = document.getElementById('not-robot');
  const progressArea = document.getElementById('progress-area');
  const progressBar = document.getElementById('progress-bar');
  const whatsappArea = document.getElementById('whatsapp-area');
  const whatsappBtn = document.getElementById('whatsapp-btn');
  const continueWrapper = document.getElementById('continue-wrapper');
  const continueBtn = document.getElementById('continue-btn');
  const channelArea = document.getElementById('channel-area');
  const channelBtn = document.getElementById('channel-btn');
  const channelContinueWrapper = document.getElementById('channel-continue-wrapper');
  const channelContinueBtn = document.getElementById('channel-continue-btn');
  const downloadArea = document.getElementById('download-area');

  openVideoBtn.addEventListener('click', () => {
    window.open(VIDEO_URL, '_blank');
    robotCheck.classList.remove('hidden');
  });

  // ...y así sigue el flujo
</script>
