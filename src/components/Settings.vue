
        <div class="form-group mb8">
          <label
            >LiveNet API Key
            <span
              class="icon-info-circle"
              title="Your API Key on testnet, with Order permissions (NOT Order Cancel)"
              v-tippy
            ></span
          ></label>
          <input
            id="apikey"
            onchange="apis();"
            type="string"
            placeholder=""
            class="form-control"
            :value="apikey"
            @change=""
          />


        </div>

        
        <div class="form-group settings-pair mb8">
          <label
            >API Secret
            <span
              class="icon-info-circle"
              title="Your API Secret - note that your API Key and Secret are kept within your browser storage, and never sent to the server"
              v-tippy
            ></span
          ></label>
          <input
            id="apisecret"
            onchange="apis();"
            type="string"
            placeholder=""
            class="form-control"
            :value="apisecret"
            @change=""
          />

        </div>
          <div class="form-group settings-pair mb8">
          <label
            >Stop loss market out
            <span
              class="icon-info-circle"
              title="The Stop Loss stop %"
              v-tippy
            ></span
          ></label>
          <input
            id="trailstop"
            onchange="apis();"
            type="string"
            placeholder=""
            class="form-control"
            :value="trailstop"
            @change=""
          />
        </div>